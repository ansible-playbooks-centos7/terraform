[![](https://github.com/ansible-roles-matsumura/terraform/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/terraform/actions?query=workflow%3Abuild)

Role Description
=========

Installs [Terraform](https://www.terraform.io) for CentOS7/CentOS8.

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
    - geerlingguy.repo-epel
    - jq
    - terraform
```

License
-------

BSD
