vmware
===========

Installs dependencies and drivers for Vagrant guests running on a
VMWare system

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
- hosts: vmware-servers
  roles:
    - role: oasis_roles.system.vmware
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
