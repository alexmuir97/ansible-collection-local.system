# Ansible Role: local.system.pcp
An Ansible role to install and configure Performance Co-Pilot (PCP).

## Description
Performance Co-Pilot (PCP) is a suite of tools, services, and libraries for monitoring, visualising, storing, and analysing system-level performance measurements.  This role may be used to install and configure Performance Co-Pilot client on a given machine. Potentially useful for persisting performance data in Cockpit.

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
        name: "local.system.pcp"
```
