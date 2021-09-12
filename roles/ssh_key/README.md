# Add SSH key

Add SSH key to target

## Role Variables

```yml
host: # Host group
user: # user that gets the key
ssh_key: # key file path ex: ~/.ssh/id-rsa
```

## Example Playbook

```yml
- hosts: '{{ host }}'
  become: yes
  vars:
    host: # Host group
    user: # user that gets the key
    ssh_key: # key file path ex: ~/.ssh/id-rsa
  roles:
    - dev01d.ssh_key
```

## License

GPL-3.0
