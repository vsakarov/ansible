Git
===

Configure git

Requirements
------------

Ubuntu system

Role Variables
--------------

- first_user.home

Dependencies
------------

- first_user

Example Playbook
----------------

```yaml
- hosts: localhost
  connection: local
  roles:
    - { role: git, tags: git }
```


License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
