# Test connection

```
ansible -i inventory/hosts.ini all -m ping
```

# Build whole system

```
ansible-playbook -i inventory/hosts.ini site.yml
```
