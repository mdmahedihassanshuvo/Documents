## How to create SSH key

```bash
ssh-keygen -t rsa -b 4096
```

```bash
cat ~/.ssh/id_rsa.pub
```

## DJANGO NECESSARY COMMAND:

```base
pip install django
```
```base
pip install django-crontab
```

## DATABASE COMMAND:

```bash
psql -U postgres -h localhost 
```
```base
create database database_name;
```
```base
drop database database_name;
```
```base
psql -U postgres psql -f file_with_path -d database_name
```
## INSTALL ALL REQUIRED PACKAGE INSTALL

```base
pip install -r requirements/development.txt 
```

```base
pip freeze > requirements.txt
```
