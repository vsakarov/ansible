First User
==========

Set variable with the name of the user with id 1000. On most unix systems this is the first created user.

Requirements
------------

System that supports the `id` command

Role Variables
--------------

This role only set variable `first_user`. Priority is high, but can be overwritten with `-e` parameter when running ansible.

Example Playbook
----------------

```yaml
- hosts: localhost
  connection: local
  roles:
    - first_user
  tasks:
    - debug:
        var: "{{ first_user.name }}"
    - debug:
        var: "{{ first_user.home }}"
```

License
-------

MIT

Author Information
------------------

https://github.com/vsakarov/
