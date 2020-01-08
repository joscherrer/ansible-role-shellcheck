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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: joscherrer.shellcheck }

License
-------

MIT

Author Information
------------------

Jonathan Scherrer