[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/terraform/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/terraform/tree/main)

Role Description
=========

Installs [Terraform](https://www.terraform.io) for CentOS7/Stream8.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

jq installed before running this role.

[ansible-roles-matsumura/jq](https://github.com/ansible-roles-matsumura/jq)

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - robertdebock.epel
    - jq
    - terraform
```

License
-------

BSD
