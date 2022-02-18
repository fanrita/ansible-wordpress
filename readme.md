# Wordpress on Ubuntu in docker

## Pre-setup

Task was done for WordPress installation in docker by ssh to Ubuntu machine in VirtualBox using Ansible.

- [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).
- [Install Ubuntu in VirtualBox](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview).
- [Enable ssh to VirtualBox machine](https://dev.to/developertharun/easy-way-to-ssh-into-virtualbox-machine-any-os-just-x-steps-5d9i).

Containers will be created with the options specified in the `vars/var.yml` variable file.

ssh info is in development.ini

NOTE: I did not use any encryption for passwords.

## Running this Playbook

```command
ansible-playbook -i [inventory file]  playbook.yml
```

with development.ini
```command
ansible-playbook -i development.ini playbook.yml
```

