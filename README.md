## Factorio Ansible role 
ansible role for deploying  a factorio server for Debian.

## Prerequisites

First of all you should install [Ansible](http://www.ansible.com/home) on your machine, official [docs](http://docs.ansible.com/intro_installation.html) should help you with that.


## Example playbook

```yml
# playbook.yml

vars:
# Set your personal minio credentials ;)
  minio_user: 'insert your use' 	 
  minio_passwd: 'insert your password' 

roles:
  - factorio_role_ansible

```
