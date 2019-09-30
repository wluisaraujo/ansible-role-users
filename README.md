[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Local%20Users-blue.svg)](https://git.io/fjRao) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-users.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-users)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [(Linux)Local Users](www.guiafoca.org/)
------------

Description
------------

 * Ansible for Manage Local Users

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.users
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.users/requirements.txt
```

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
    - users
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)