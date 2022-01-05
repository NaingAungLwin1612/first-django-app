# First django app

## Create virtual environment

`python -m venv .tutorial-env`

## Activate virtual environment

`.tutorial-env\Scripts\activate`

## Install dependencies

`python -m pip install -r requirements.txt`

## Change dir to ./mysite

`cd django-app`

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

## Testing

`py manage.py test polls`
