# Role Name

Install LAMP stack

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
    - dev01d.lamp
```

## License

GPL-3.0
