# ansible_atlassian-confluence
Ansible playbook for installing Confluence, AdoptOpenJDK, Postgres, and NGINX into remote machine running Ubuntu

## Quick Start
* Clone the repo:
```
git clone https://github.com/stephenbrannen/ansible_ubuntu-atlassian-confluence-stack.git && cd ansible-playbooks
```
* Install ansible if needed; see [instructions](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
* Edit site.yml to adjust variables as needed
* Deploy the playbook
```
ansible-playbook site.yml
```

## Development Environment Tested OS (using at least 4GB of memory):
* ubuntu:20.04
