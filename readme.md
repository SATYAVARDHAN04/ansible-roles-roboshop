# DEVELOPING ROBOSHOP PROJECT USING ANSIBLE ROLES 

## 1. MONGODB ROLE

```bash
ansible-playbook -i inventory.ini -e componenet=mongodb main.yaml
```

## 2. CATALOGUE ROLE

```bash
ansible-playbook -i inventory.ini -e componenet=catalogue main.yaml
```