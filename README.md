# acm-aap-integration

> An example repo to integrate Red Hat Advanced Cluster Management and Ansible Automation Platform

This repository is meant to demonstrate how AAP and ACM can be integrated in order to do lifecycle automation of clusters as they're created/imported/updated/deleted/detached.

## Contents

- `.azure` - Azure DevOps Pipelines to build the Execution Environment for this repo.  See Documentation for [Setting Up Azure DevOps](https://github.com/kenmoini/ansible-ee-builder/blob/main/docs/azure-devops-setup.md)
- `.github` - GitHub Actions to build the Execution Environment for this repo.
- `controller_config` - Ansible Automation that can be run to set up Ansible Automation Controller with the various Inventories, Applications, Tokens, Projects, and Job Templates.
- `execution_environment` - The Execution Environment definition for this repository.  Has helpful binaries and collections pre-installed.
- `playbooks` - Ansible Playbooks (???!!???)

