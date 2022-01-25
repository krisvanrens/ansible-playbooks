# Ansible playbooks

[Ansible](https://www.ansible.com/) playbooks for automated maintenance tasks.

## Install ansible

Install Ansible first, see [here](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

## Usage

Run each playbook as follows:

```
$ ansible-playbook playbook.yml --extra-vars "inventory=.."
```

Provide your hosts or host groups as an argument to parameter `inventory`.

### Extra parameters

Some playbooks have extra parameters:

- `update-system.yml`

  - `reboot_default=true|false`: Reboot the system after updating, regardless.
