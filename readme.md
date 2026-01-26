# DEVELOPING ROBOSHOP PROJECT USING ANSIBLE ROLES 

## 1. MONGODB ROLE

```bash
ansible-playbook -i inventory.ini -e componenet=mongodb main.yaml
```

## 2. CATALOGUE ROLE

```bash
ansible-playbook -i inventory.ini -e componenet=catalogue main.yaml
```

## 3. FRONTEND ROLE

```bash
ansible-playbook -i inventory.ini -e componenet=frontend main.yaml
```


# WORKING WITH ANSIBLE VAULT

## 1. CREATING ANSIBLE VAULT

```bash
ansible-vault create filename.yaml
```

## 2. EDITING ANSIBLE VAULT

```bash
ansible-vault edit filename.yaml
```

## 3. VIEWING ANSIBLE VAULT

```bash
ansible-vault view filename.yaml
```

## 4. DELETING ANSIBLE VAULT

```bash
ansible-vault delete filename.yaml
```

## 5. CHANGING PASSWORD OF ANSIBLE VAULT

```bash
ansible-vault rekey filename.yaml
```
