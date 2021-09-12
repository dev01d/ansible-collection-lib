# Ansible roles

Reusable ansible roles

Example config files can be placed in root of project's `ansible` dir.

- ansible.cfg

```properties
[defaults]
inventory = ./hosts.ini
```

- hosts.ini

```ini
[all:vars]
ansible_user=
; ansible_port=22
; ansible_become=yes
ansible_python_interpreter=/usr/bin/python3
ansible_ssh_common_args='-o StrictHostKeyChecking=no'
; ansible_ssh_private_key_file=

[server]
server1 ansible_host=

[nodes]
node1 ansible_host=
node2 ansible_host=
```
