# Fedora Workstation Ansible

## Overview

### Description
- A base playbook for new EC2
- Provides installation and opinionated configurations for:
    - aws-cli
    - pyenv-pipenv
    - nodejs-nvm


## Prerequisites
- Fedora 41
- Python 2.4
- Ansible 2.14.11

## User Manual

**Getting Started**
- Fork and Clone Repository.

```
   git clone https://github.com/aaronfeingold/ajf-ansible.git
   cd ajf-ansible
```
**Prerequisite CLI**
- Use the interactive bash setup if need be (will be prompted for passwords)
```
chmod +x setup/prerequisites
./setup/prerequisites
```
**Execute Playbook**
```
chmod +x run_playbook
./run_playbook
```

