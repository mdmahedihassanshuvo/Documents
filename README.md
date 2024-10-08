## HOW TO CREATE A PROJECT

```base
mkdir folder_name
```

```base
python -m pip install Django
```

```base
django-admin startproject mysite
```

```base
python3 -m venv myenv
```

```base
python manage.py startapp app_name
```

```base
python manage.py runserver
```

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
django-admin startproject app_name
```

```base
pip install django-crontab
```

```base
pip install djangorestframework
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
psql -U postgres -h localhost -d rhd_dbs -f /home/shuvo/Downloads/rhd_dms_db_2024_09_28_12_00.psql
```
```base
pg_dump -U postgres -h localhost -d tiger_one_dphe_dbs -f /home/shuvo/Downloads/backup_file_name.psql
```
## INSTALL ALL REQUIRED PACKAGE INSTALL

```base
pip install -r requirements/development.txt 
```

```base
pip freeze > requirements.txt
```

## GITHUB NECESSARY COMAND

```base
git branch
```

```base
git add .
```

```base
git commit -m
```

```base
git branch -a
```

```base
git checkout
```

```base
git checkout main
```

```base
git marge main
```

```base
git pull
```
## HOW TO INSTALL XAMPP

```base
wget https://sourceforge.net/projects/xampp/
```

```base
cd Downloads
```

```base
chmod 755 xampp-linux-*-installer.run
```

```base
sudo ./xampp-linux-*-installer.run
```

```base
sudo /opt/lampp/lampp stop

```base
sudo /opt/lampp/lampp start
```
## PYTHON INSTALLATION

```base
sudo dnf -y install bzip2-devel cairo cairo-devel cryptopp-devel \
expat-devel gdal gdal-devel libffi-devel libpcap-devel libcurl-devel \
libxml2-devel ncurses-devel openssl-devel proj proj-devel python3-devel \
pango pango-devel readline-devel sqlite-devel tk-devel \
xz-devel xerces-c-devel zlib-devel
```

```base
cd /tmp/ && wget https://www.python.org/ftp/python/3.8.15/Python-3.8.15.tgz &&
tar xzf Python-3.8.15.tgz && cd Python-3.8.15 && ./configure --enable-optimizations &&
make && sudo make altinstall && python3.8 --version
```

