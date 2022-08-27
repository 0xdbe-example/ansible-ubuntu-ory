# Ansible Ubuntu - ORY


## Usage

- Set env vars in ``vars/main.yml``:

```
database_name:
database_username:
database_password:
kratos_version:
```

- Deploy 

```
ansible-playbook --inventory inventories/hosts playbook.yml
```
