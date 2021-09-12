# Ansible Collection - dev01d.lib

## Install

```shell
ansible-galaxy collection install dev01d.lib
```

### Requirements file

```yml
---
collections:
  - dev01d.lib
  #! or
  - name: hhttps://github.com/dev01d/ansible-collection-lib.git
    type: git
```

## Usage

### Role Variables

```yml
host: # Host group
```

### Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
  roles:
    - dev01d.lib.upgrade
```

## License

GPL-3.0
