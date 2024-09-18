# Fedora Workstation Ansible

## Overview

### Description
- A base playbook for new EC2
- Provides installation and configuration for:
  - AWS CLI
  - Pyenv
  - Pipenv

## Prerequisites
- Fedora 37 workstation
- Python 2.4
- Ansible 2.14.11

## User Manual

**Getting Started**
- Fork and Clone Repository.

```
   git clone https://github.com/aaronfeingold/ajf-ansible.git
   cd ajf-live-re-wire
```
**Prerequisite CLI**
- Use if need be.
```
chmod +x setup/prerequisites
./setup/prerequisites
```
**Execute Playbook**
```
chmod +x run_playbook
./run_playbook
```

