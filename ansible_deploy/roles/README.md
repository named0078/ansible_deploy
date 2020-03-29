# Ansible Role: 

Install on RedHat/CentOS linux servers

"geerlingguy.java" and "geerlingguy.jenkins" role are download from: https://galaxy.ansible.com/geerlingguy/jenkins/

## Requirements

Can ssh login remote target instance and have root permission

## Role Variables

All available variables are created in ../common/vars/main.yml

## Example Playbook

```yaml
- hosts: target_host
  roles:
  - role: common
  - role: git
```

## Author Information

These roles were created in 2017 by [Peiwen Jia](named007@163.com), Dependence on  - Gerrit  Project - 

