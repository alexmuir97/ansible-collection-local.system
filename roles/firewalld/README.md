# Ansible Role: local.system.firewalld
An Ansible role to install and configure firewalld.

## Description
The role installs and configures firewalld and ensures that the service is running and properly configured.

## Dependencies
None.

## Conflicts
None.

## Variables
The role comes with default variables (via `defaults/main.yml`), which can be overridden.

## Additional hints
None.

## Examples
The below examples should help to explain how the role can be used.

```yaml
# Simple example with defaults

- name: "Examples for the usage"
  hosts: "all"

  tasks:

    - name: "Example with defaults"
      ansible.builtin.import_role:
        name: "local.system.firewalld"
```
