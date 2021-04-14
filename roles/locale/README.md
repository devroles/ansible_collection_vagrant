locale
===========

Sets system locale

Requirements
------------

Ansible 2.8 or higher

Role Variables
--------------

Currently the following variables are supported:

### General


Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: locale-servers
  roles:
    - role: oasis_roles.system.locale
```

License
-------

GPLv3

Author Information
------------------

Greg Hellings <greg.hellings@gmail.com>
