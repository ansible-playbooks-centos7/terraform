[![](https://github.com/ansible-roles-matsumura/terraform/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/terraform/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/terraform/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/terraform/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/terraform/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/terraform/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/terraform/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/terraform/actions?query=workflow%3Ayamllint)

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
