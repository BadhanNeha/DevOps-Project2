<<<<<<< HEAD
## Ansible

- open  source automation tool used for configuration management, application deployment and orchestration
- Uses SSH to connect with server - no agent installation needed
- Pushed based mechanism
Written in YAML files called as playbook

## inventory

- inventory.ini
- lists of target hosts.

## Idempotent

- Run multiple timeswon't break the setup

## Install Nginx and startthe service and enabled it with YAML

## Commands

- ansible host -i inventory.ini -m ping (To check that specific server is working or not)

- ansible-playbook -i inventory.ini Install-nginx.yml  (to run playbook) 

- sudo apt install ansible -y  (Install ansible)

