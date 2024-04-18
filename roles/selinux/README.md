# Ansible Role: local.system.selinux
An Ansible role to install and configure selinux.

## Description
This role ensures that SELinux is in the desired state and that additional troubleshooting/management packages are present alongside.

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
        name: "local.system.selinux"
```
