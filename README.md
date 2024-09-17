# Fedora Workstation Ansible

## Overview

### Description
- A base playbook for new EC2
- Provides install configuration for:
  - AWS CLI
  - Pyenv
  - Pipenv

## Contents

### Prerequisites
- Fedora 37 workstation
- Python 2.4
- Ansible 2.14.11
- AWS User Account + Credentials
  - <AWS_ACCESS_KEY_ID>
  - <AWS_SECRET_ACCESS_KEY>

### User Manual

**Getting Started**
- Fork and Clone Repository

```
   git clone https://github.com/aaronfeingold/ajf-ansible.git
   cd ajf-live-re-wire
```
**Prerequisite CLI**
- This will configure AWS envs vars by user
- Note: must have AWS creds ready to set in environment
  - note: default region and output are given if non provided
```
chmod +x setup/prerequisites
./setup/prerequisites
```
- Execute playbook
```
chmod +x run_playbook
./run_playbook
```

