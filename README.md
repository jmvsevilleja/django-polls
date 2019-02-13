Django

Prereq
- Python 3
- Pip

Create a new virtual environment by running:
    `python3 -m venv ~/.virtualenvs/djangodev`
    win: `mkvirtualenv myproject`

to activate it:
    `source ~/.virtualenvs/djangodev/bin/activate`
    win: `workon myproject`

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

Running tests
    `python manage.py test polls`

Creating Package (setuptools pip)
    `python setup.py sdist`

Installing Package
    `pip install django-polls/dist/django-polls-alpha-0.1.tar.gz`

Uninstall Package
    `pip uninstall django-polls-alpha`

Uploading dist to pypi (twine)
    `python -m twine upload --repository-url https://test.pypi.org/legacy/ dist/*`

Installing from pypi
    `pip install -i https://test.pypi.org/simple/ django-polls-alpha==0.1`

List all packages
    `pip list`

Show package details
    `pip show <package-name>`
