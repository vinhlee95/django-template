# Django boilerplate
A boilerplate for Django backend projects

## Technologies
- [Poetry](https://python-poetry.org/docs/): Python package manager
- [Django](https://www.djangoproject.com/): Python backend framework

## Install packages
`poetry install`

## Run migration and run server
```bash
poetry shell
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```