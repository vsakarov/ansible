Role Name
=========

Install docker and docker-compose from official docker repo.

Requirements
------------

Ubuntu system

Role Variables
--------------

- first_user.name

Dependencies
------------

- first_user

Example Playbook
----------------

```yaml
- hosts: local
  roles:
    - { role: docker-install, tags: ['docker-install', 'docker'] }
```


License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
