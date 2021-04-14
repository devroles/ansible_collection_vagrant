virtualbox
===========

Installs dependencies and the Virtualbox Guest Additions to the
guest system so that it can already be installed

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
- hosts: virtualbox-servers
  roles:
    - role: oasis_roles.system.virtualbox
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
