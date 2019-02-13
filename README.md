Django

Prereq
- Python 3
- Pip

Create Virtual Environment:
    `python3 -m venv ~/.virtualenvs/djangodev`
    win: `mkvirtualenv myproject`

Activate Environment:
    `source ~/.virtualenvs/djangodev/bin/activate`
    win: `workon myproject`

Install Django
    `pip install Django`

Check Django Version
    `python -m django --version`

Update Django Latest Version
    `pip install django --upgrade`

Create project
    `django-admin startproject mysite`

Run a server
    `python manage.py runserver 1.2.3.4:8080`

Kill server
    `ps -ef | grep python`
    `kill -9 process_id`

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


ADMIN

Creating admin user
    `python manage.py createsuperuser`
Locate Django source files
    `python -c "import django; print(django.__path__)"`


TWIG