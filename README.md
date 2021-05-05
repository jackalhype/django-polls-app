# DJANGO 3.2 SIMPLE POLLS APPLICATION
Just from the docs

## Developed with:
`python 3.7`
`Django Framework 3.2`
`sqlite3 3022000`
`pipenv 2020.11.15`

## Commands used:
django-admin startproject minniproj

python manage.py runserver

python manage.py startapp polls

python manage.py migrate

python manage.py makemigrations polls
    
python manage.py sqlmigrate polls 0001
    # show migration sql

python manage.py check
    # check for any errors in conf

python manage.py migrate

python manage.py createsuperuser
    # boss:1234

python manage.py shell
    # run console python

python manage.py test polls
    # run tests for polls app
    
python manage.py collectstatic
    # if admin css, js disappers suddenly
    
from django.db import connection
print(connection.queries)
    # list of sqls

