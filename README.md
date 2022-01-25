# Ansible playbooks

Ansible playbooks for automated tasks.

## Install ansible

Install Ansible first, see [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

## Usage

Run as follows:

```
$ ansible-playbook playbook.yml --extra-vars "inventory=.."
```

Some playbooks have extra parameters:

- `update-system.yml`:
  - `reboot_default=true|false`: Reboot the system after updating, regardless.
