# First django app

## Create virtual environment

`python -m venv .tutorial-env`

## Activate virtual environment

`.tutorial-env\Scripts\activate`

## Change dir to ./mysite

`cd mysite`

## Migrate database

`python manage.py makemigrations`

`python manage.py migrate`

## Create admin

`python manage.py createsuperuser`

*** Add user name, email and password. ***

## Run app

`py manage.py runserver`

### Admin pannel

[/admin/](http://localhost:8000/admin/)

### Poll app

[/polls/](http://localhost:8000/polls/)
