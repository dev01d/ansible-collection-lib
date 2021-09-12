# MySQL server

Install Mysql server

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
    - dev01d.mysql_server
```

## License

GPL-3.0
