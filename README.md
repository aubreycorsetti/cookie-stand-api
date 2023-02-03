# Lab 34

Template Project for starting up CRUD API with Django Rest Framework

username: admin
password: password

## SetUp

> create venv
> pip install -r requirements.txt
> python -c "import secrets; print(secrets.token_urlsafe())"
> python manage.py makemigrations
> python manage.py migrate
> python manage.py createsuperuser
> python manage.py runserver

## Database

> https://api.elephantsql.com/
DATABASE_ENGINE=django.db.backends.postgresql
DATABASE_NAME=fdxxhkay
DATABASE_USER=fdxxhkay
DATABASE_PASSWORD=itCHeY0Xuk7lVZrmZ7EcQlojt4vE_1MN
DATABASE_HOST=kashin.db.elephantsql.com
DATABASE_PORT=5432

**NOTE:** If you are using Postgres instead of SQLite then make sure to install `psycopg2-binary` and include in `requirements.txt`
