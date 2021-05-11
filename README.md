# django-bootstrap

Disclaimer : This is the resulting code from a pluralsight course

## Install django
```bash
python -m pip install django
```

## Create django project 
```bash
django-admin startproject my-projct-name
```

## Run
```bash
# Into the actually directory
cd my-project-name

# Dev server 
python manage.py runserver
```

## Add "app" to django 
``bash
python3 manage.py startapp website
``

## Migrations
```bash
python3 manage.py shomigrations
# initial migrations stored in db.sqlite3
python3 manage.py migrate 

## connect to sqllite 
python3 manage.py dbshell
```
