# Ansible

This repo contains playbooks for recreating my Ubuntu based workstation. May contain useful code.

## Usage


### From remote repo
```bash
sudo add-apt-repository universe && sudo apt install ansible git
export ANSIBLE_FORCE_COLOR=true
sudo true && ansible-pull -U https://github.com/vsakarov/ansible/ single.yaml -e task=XXXXX --check
```

### Local clone
```bash
sudo add-apt-repository universe && sudo apt install ansible git
git clone https://github.com/vsakarov/ansible.git
cd ansible
sudo true && ansible-playbook single.yaml --diff -e task=XXXXX --check
```
