# Ansible Automation Platform Config as Code example repository

This is an example repository for utilizing the infra.aap_configuration collection to push configs to AAP. The intent is to keep it as simple as possible for those new to the collection.

## Requirements

The following collections are required

```yaml
---
collections:
  - name: ansible.controller
  - name: infra.aap_configuration 