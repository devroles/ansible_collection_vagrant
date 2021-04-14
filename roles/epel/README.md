epel
===========

Installs the epel-release package into a CentOS/RHEL system, but disables it
so that the machine still behaves according to default behaviors.

Requirements
------------

Ansible 2.8 or higher

Red Hat Enterprise Linux 7 or equivalent

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
- hosts: epel-servers
  roles:
    - role: oasis_roles.system.epel
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
