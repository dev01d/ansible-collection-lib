# NFS client

Install NFS client

## Role Variables

```yml
host: # Host group
user: # user name for home mount path
nfs_ip: # private IP of NFS server
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
    user: # user name for home mount path
    nfs_ip: # private IP of NFS server
  roles:
    - dev01d.nfs_client
```

## License

GPL-3.0
