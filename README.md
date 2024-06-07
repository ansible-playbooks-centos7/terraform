[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/terraform/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/terraform/tree/main)

Role Description
=========

Installs [Terraform](https://www.terraform.io) for CentOS Stream 9.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

[EPEL](https://docs.fedoraproject.org/en-US/epel/) and [jq](https://github.com/stedolan/jq) installed before running this role.

[ansible-roles-matsumura/jq](https://github.com/ansible-roles-matsumura/jq)

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.epel
    - andrewrothstein.jq
    - terraform
```

License
-------

BSD
