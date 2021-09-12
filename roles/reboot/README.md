# Reboot

Reboot server

## Role Variables

```yml
host: # Host group
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  order: sorted
  vars:
    host: # Host group
  roles:
    - dev01d.reboot
```

## License

GPL-3.0
