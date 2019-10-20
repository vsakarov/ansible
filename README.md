# Ansible

This repo contains playbooks for recreating my Ubuntu based workstation. May contain useful code.

## Usage


### From remote repo
```bash
sudo add-apt-repository universe && sudo apt install ansible git
# dconf module is part ansible version 2.4, so ppa repo may be needed
sudo true && ansible-pull -U https://github.com/vsakarov/ansible/ install-ansible-from-ppa.yaml
sudo true && ansible-pull -U https://github.com/vsakarov/ansible/ break-stuff.yaml --tags XXXXX --check
sudo true && ansible-pull -U https://github.com/vsakarov/ansible/ single.yaml -e task=XXXXX --check
```

### Local clone
```bash
sudo add-apt-repository universe && sudo apt install ansible git
git clone https://github.com/vsakarov/ansible.git
cd ansible
sudo true && ansible-playbook install-ansible-from-ppa.yaml
sudo true && ansible-playbook break-stuff.yaml --list-tags
sudo true && ansible-playbook break-stuff.yaml --diff --tags XXXXX --check
sudo true && ansible-playbook single.yaml --diff -e task=XXXXX --check
```
