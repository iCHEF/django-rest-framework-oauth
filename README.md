# djangorestframework-oauth

[![build-status-image]][travis]
[![pypi-version]][pypi]

## Overview

OAuth support for Django REST Framework

## Requirements

* Python (2.7, 3.3, 3.4)
* Django (1.6, 1.7)

## Installation

Install using `pip`...

```bash
$ pip install djangorestframework-oauth
```

## Testing

Install testing requirements.

```bash
$ pip install -r requirements-test.txt
```

Run with runtests.

```bash
$ ./runtests.py
```

You can also use the excellent [tox](http://tox.readthedocs.org/en/latest/) testing tool to run the tests against all supported versions of Python and Django. Install tox globally, and then simply run:

```bash
$ tox
```

## Documentation

To build the documentation, you'll need to install `mkdocs`.

```bash
$ pip install mkdocs
```

To preview the documentation:

```bash
$ mkdocs serve
Running at: http://127.0.0.1:8000/
```

To build the documentation:

```bash
$ mkdocs build
```


[build-status-image]: https://secure.travis-ci.org/jpadilla/django-rest-framework-oauth.png?branch=master
[travis]: http://travis-ci.org/jpadilla/django-rest-framework-oauth?branch=master
[pypi-version]: https://pypip.in/version/django-rest-framework-oauth/badge.svg
[pypi]: https://pypi.python.org/pypi/django-rest-framework-oauth