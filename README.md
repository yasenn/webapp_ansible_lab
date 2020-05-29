# Web app setup with `Ansible`

This repo installs `PostgreSQL` and `Nginx` on the virtual machines.
You can provision new VMs or use existing.

# Table of Contents

 - [Installation](#Installation)
 - [Provisioning](#Provisioning)
 - [Setup PostgreSQL](#PostgreSQL)
 - [Setup Nginx](#Nginx)


# Installation

To ensure that `ansible` is installed on your machine, run check-and-setup-ansible.sh

After that, ` ansible --version` should work and report current `ansible` version info.

# Provisioning

To provisioning results before creating VMs, use command

```sh
ansible-playbook -CD -i localhost provision.yml
```

To provision VMs, use command

```sh
ansible-playbook -D -i localhost provision.yml
```

# PostgreSQL

# Nginx

# TODO

- PostgreSQL playbook
- Nginx playbook
- Setup script
- Developer manual with command line options and used tags
