# Ansible Role: local.system.networkmanager
An Ansible role to install and configure NetworkManager.

## Description
NetworkManager is a program for providing detection and configuration for systems to automatically connect to networks, useful for both wireless and wired networks. This role configures the essential NetworkManager packages and services whilst also providing the ability to manage connections (e.g ethernet and VLAN) using nmcli.

## Dependencies
None.

## Conflicts
None.

## Variables
The role comes with default variables (via `defaults/main.yml`), which can be
overridden.

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
        name: "local.system.networkmanager"
```
