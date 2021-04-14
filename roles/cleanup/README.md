cleanup
===========

Cleans up a VM near the end of the provisioning stage

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
- hosts: cleanup-servers
  roles:
    - role: oasis_roles.system.cleanup
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
