andrewrothstein.vault
=====================
[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-vault.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-vault)

Install's [Hashicorp's Vault](https://www.vaultproject.io/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```
- hosts: servers
  roles:
    - andrewrothstein.vault
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
