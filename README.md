[![CircleCI](https://dl.circleci.com/status-badge/img/gh/ansible-roles-mamono210/postgresql/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/ansible-roles-mamono210/postgresql/tree/main)

Role Description
=========

Install [PostgreSQL](https://www.postgresql.org) for CentOS Stream 8.

Requirements
------------

None

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
    - postgresql
```

License
-------

BSD
