ansible-role-ferm-basic
=====

This role installs [ferm](http://ferm.foo-projects.org/). 
This role has only been tested in Debian.

Requirements
------------

This role requires Ansible 1.6 or higher.


Role Variables
--------------

All these variables are defined in vars/main.yml and will be used by default.

    ## set to true if the host where the role is running is configured to block
    ## all outbound traffic except tor
    usetor: true

Dependencies
------------


Example Playbook
----------

```
- hosts: localhost

  roles:

    - { role: ansible-role-ferm-basic
      }
      }
```

License
-------

GPLv3

Author Information
------------------

Lee Woboo

