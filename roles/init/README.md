init
===========

Configures sustems that use init instead of systemd for Vagrant usage

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
- hosts: init-servers
  roles:
    - role: oasis_roles.system.init
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
