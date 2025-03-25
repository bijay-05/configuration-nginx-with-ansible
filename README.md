# configuration-nginx-with-ansible
This repository contains documentation and snippets on how to configure nginx web server with Ansible.

## Launching an EC2 instance in AWS with available AMIs.
We launched an `t2.micro` EC2 instance in AWS cloud.

## Create Ansible Inventoy
Ansible inventory is a collection of nodes or machines to be managed by ansible. Inventories can be defined in either `inventory.ini` or `inventory.yaml` file. Since our requirement is small scale with just single machine, we go with `inventory.ini`.

## Ansible Playbook
