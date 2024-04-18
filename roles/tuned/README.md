# Ansible Role: local.system.tuned
An Ansible Role to install and configure the Tuned service.

## Description
This role installs and configures Tuned, a system tuning service for Linux. by default, Tuned it is distributed with a number of predefined profiles for common use cases like high throughput, low latency, or powersave but it is possible to modify the rules defined for each profile and customise how to tune a particular device. 

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
        name: "local.system.tuned"
```
