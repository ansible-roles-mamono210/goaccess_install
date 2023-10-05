[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/goaccess_install/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/goaccess_install/tree/main)

Role Description
=========

Install [GoAccess](https://goaccess.io) for CentOS Stream.

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
