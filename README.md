# Ansible role: nodejs
Node.js application server

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `node_ver`: version to install from nodesource, e.g., `14.x`

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run prior to removing host from inventory group.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
