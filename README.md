# WordPress Ansible Playbook

- Requires Ansible 1.2 or newer
- Expects Ubuntu 14.04

This playbook deploys an optimized setup for WordPress using MariaDB, nginx, PHP FPM, and Memcached.

## Optional Roles

* Backup - This role will backup your files and database to Amazon S3
* Letsencrypt - This role is a work in progress. It setups LetsEncrypt for generating SSL certificates.

## Example Hosts file

`hosts.example` contains an example host. Just substitute your information, and you should be good to go.