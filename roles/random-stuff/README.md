Random stuff
============

Sandbox role for stuff that still don't have separate role

- Fix pwm settings for lenovo x220 laptop.

Requirements
------------

Ubuntu system

Role Variables
--------------

- first_user.name
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
    - { role: random-stuff, tags: random-stuff }
```


License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
