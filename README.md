# Django-Heroku Project Template

Bare bones Django project template ready to be deployed to Heroku.

## Requirements

* [Python 3.*](http://install.python-guide.org)
* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

## Running Locally

```sh
$ python3 -m venv core
$ pip install -r requirements.txt

$ createdb core

$ python3 manage.py migrate
$ python3 manage.py collectstatic

$ heroku local
```

Open [localhost:5000](http://localhost:5000/) in a web browser.

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master

$ heroku run python manage.py migrate
$ heroku open
```

## More Information

* [Django](https://docs.djangoproject.com/en/3.1/)
* [Python on Heroku](https://devcenter.heroku.com/categories/python)