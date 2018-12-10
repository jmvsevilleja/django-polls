Django

Prereq
- Python 3
- Pip

Create a new virtual environment by running:
    `python3 -m venv ~/.virtualenvs/djangodev`

to activate it:
    `source ~/.virtualenvs/djangodev/bin/activate`

install Django
    `pip install Django`

check Django Version
    `python -m django --version`

Create project
    `django-admin startproject mysite`

Run a server
    `python manage.py runserver 1.2.3.4:8080`

Apply database migrations
    `python manage.py migrate`

Add app
    `python manage.py startapp polls`

Create model tables in database
    `python manage.py migrate`

Prepare changes to your models
    `python manage.py makemigrations polls`

Check Problems
    `python manage.py check`

Interactive Python Shell
    `python manage.py shell`

