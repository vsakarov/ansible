Editors
=========

Install emacs and vim editors with basic configuraions

Requirements
------------

Ubuntu system

Role Variables
--------------

- dot_spacemacs_url

Dependencies
------------

Example Playbook
----------------

```yaml
- hosts: localhost
  connection: local
  roles:
    - { role: editors, tags: editors }
```


License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
