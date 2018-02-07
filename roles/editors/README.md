Role Name
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

- first_user

Example Playbook
----------------

```yaml
- hosts: local
  roles:
    - { role: editors, tags: editors }
```


License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
