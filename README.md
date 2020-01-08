ansible-role-shellcheck
=========

This role installs shellcheck from source

Requirements
------------

None

Role Variables
--------------

```
shellcheck_force_install: false
shellcheck_install_version: "7.0.0"
```

Dependencies
------------

geerlingguy.git

Example Playbook
----------------

```
- hosts: all
  roles:
    - { role: joscherrer.shellcheck }
```

License
-------

MIT

Author Information
------------------

Jonathan Scherrer