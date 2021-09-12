# NFS server

Install NFS server

## Role Variables

```yml
host: # Host group
user: # user name for home mount path
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
    user: # user name for home mount path
  roles:
    - dev01d.nfs_server
```

## License

GPL-3.0
