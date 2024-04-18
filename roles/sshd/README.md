# Ansible Role: local.system.sshd
An Ansible role to install and configure OpenSSH server.

## Description
OpenSSH is a connectivity tool for remote sign-in that uses the SSH protocol. This role manages the installation of OpenSSH server and its configuration, providing basic security improvements over what is typically configured in a default installation.

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
        name: "local.system.sshd"
```
