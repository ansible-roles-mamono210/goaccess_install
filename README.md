[![](https://github.com/ansible-roles-mamono210/goaccess_install/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/goaccess_install/actions?query=workflow%3Abuild)

Role Description
=========

Install [GoAccess](https://goaccess.io) for CentOS Stream 8.

Requirements
------------

Before running this role, Epel installed on the target system.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - goaccess_install
```

License
-------

BSD
