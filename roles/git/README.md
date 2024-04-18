# Ansible Role: local.system.git
An Ansible role to install and configure git.

## Description
Git is used in many development scenarios but also for production systems that facilitate GitOps-alike deployments. This role can be used to configure git on a workstation or server deployment.

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
        name: "local.system.git"
```
