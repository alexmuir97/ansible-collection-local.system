# Ansible Role: epel
<!-- TODO: Provide a high-level role description.

e.g An Ansible role to install and configure Cockpit. -->

## Description
<!-- TODO: Elaborate on the role's purpose and functionality.

e.g The role orchestrates the installation of the Cockpit Web interface, ensuring seamless setup, service initiation, and firewall configuration if required. It also intelligently detects the presence of related software, such as Podman or KVM, and installs corresponding Cockpit applications to enhance compatibility and functionality. This role aims to simplify the deployment and management of Cockpit across diverse environments. -->

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
        name: "epel"
```
