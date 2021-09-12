# Upgrade

Upgrade Linux packages.

## Role Variables

```yml
host: # Host group
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
  roles:
    - dev01d.upgrade
```

## License

GPL-3.0
