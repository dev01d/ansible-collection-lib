# add_user

Add a Linux user

## Role Variables

```yml
host: # Host group
user: # desired user name
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
    user: # desired user name
  roles:
    - dev01d.add_user
```

## License

GPL-3.0
