# Ansible Automation Platform Config as Code Example Repository

This repository is a simple example of using the `infra.aap_configuration` collection to push configurations to the Ansible Automation Platform (AAP). It is designed to be straightforward for newcomers to the collection.

## Requirements

The following collections are required:

```yaml
---
collections:
- name: ansible.controller
- name: infra.aap_configuration
```

## Required Variables

You need to define the following variables:

```yaml
---
aap_config_controller_host: # The hostname of your AAP instance
aap_config_controller_user: # The username for the AAP instance
aap_config_controller_pass: # The password for the AAP instance
```

## Mock Data

Sample data is provided in the variable files. Please replace this with information relevant to your setup.
