# ansible-role-nodebb
Tested on Ansible 2.4.2 and Ubuntu 16.04

## Playbook sample
This playbook installs nodebb

```yaml
- hosts: nodebb_host
  become: yes
  roles:
    - role: nodebb
      admin_user: MONGODB_ADMIN_USER
      admin_password: MONGODB_ADMIN_PASS
      nodebb_user: MONGODB_NODEBB_USER
      nodebb_password: MONGODB_NODEBB_PASS
```
