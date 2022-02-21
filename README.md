# Sample django app

This is a basic app created by following the [Django getting started tutorial](https://docs.djangoproject.com/en/4.0/intro/tutorial01/).

## Installation

1. Create a virtualenv: `python3 -m venv ./venv`
1. Activate the virtualenv `source venv/bin/activate`
1. Install Django following [instructions here](https://docs.djangoproject.com/en/4.0/intro/install/)

## Setting up the app

1. Make migrations with `python manage.py makemigrations polls`
1. Run migrations with `python manage.py migrate`
1. Create a superuser with `python manage.py createsuperuser`
1. Use username admin, email admin@example.com and password UsablAdmin

## Using the site

1. Start webserver with `python manage.py runserver`
1. Open up localhost:8000/admin or http://127.0.0.1:8000/admin in your browser
1. Create a question to ask users of your website, following [instructions here](https://docs.djangoproject.com/en/4.0/intro/tutorial02/#explore-the-free-admin-functionality)
