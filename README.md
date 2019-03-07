[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-local-users.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-local-users)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [(Linux)Local Users](www.guiafoca.org/)
------------

Description
------------

 * Ansible for Manage Local Users

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-local-users
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
