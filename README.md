# Personal homepage

## Getting Started

To start Django's development server:

```
python manage.py runserver
```

To generate scripts in the migrations folder that migrate the database from its current state to the new state run:

```
python manage.py makemigrations
```

To apply the scripts to the actual database run:

```
python manage.py migrate
```

## Packages

To install packages with pip:

```
pip install -r requirements.txt
```

## Create admin to work with the database

To create admin:

```
python manage.py createsuperuser
```

## Collect static files

To collect the static files:

```
python manage.py collectstatic
```

## About

The project is based in the LinkedIn course 'Building a Personal Portfolio with Django' https://www.linkedin.com/learning/building-a-personal-portfolio-with-django