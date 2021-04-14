vagrant
===========

Configures a system for the vagrant user and SSH connectivity

Requirements
------------

Ansible 2.8 or higher

Role Variables
--------------

Currently the following variables are supported:

### General

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: vagrant-servers
  roles:
    - role: oasis_roles.system.vagrant
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
