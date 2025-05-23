# Ansible role: nodejs
Node.js application server

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `nodejs_ver` (default: '24.x'): version to install from nodesource
+ `nodejs_src` (default: 'deb.nodesource.com'): mirror to use
+ `nodejs_key`: URL to GPG key for apt repo
+ `nodejs_repo`: URL to apt repo

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run prior to removing host from inventory group.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
