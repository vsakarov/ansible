# Ansible

This repo contains playbooks for recreating my Ubuntu based workstation. May contain useful code.

## Usage

### From remote repo
```bash
sudo apt install ansible
sudo ansible-pull -U https://github.com/vsakarov/ansible/ install-ansible-from-ppa.yml
sudo ansible-pull -U https://github.com/vsakarov/ansible/ break-stuff.yml --tags XXXXX
```

### Local clone
```bash
sudo apt install ansible
git clone https://github.com/vsakarov/ansible.git
cd ansible
sudo ansible-playbook install-ansible-from-ppa.yml
sudo ansible-playbook break-stuff.yml --list-tags
sudo ansible-playbook break-stuff.yml --tags XXXXX
```
