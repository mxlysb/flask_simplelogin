[![Travis](https://img.shields.io/travis/cuducos/flask_simplelogin.svg?style=flat-square)](https://travis-ci.org/cuducos/flask_simplelogin)
[![PyPI](https://img.shields.io/pypi/v/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![PyPI versions](https://img.shields.io/pypi/pyversions/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![PyPI formats](https://img.shields.io/pypi/format/flask_simplelogin.svg?style=flat-square)](https://pypi.org/project/flask_simplelogin/)
[![Flask](https://img.shields.io/badge/Flask-Extension-blue.svg?style=flat-square)](https://github.com/pallets/flask)

# Login Extension for Flask

The simplest way to add login to flask!

## Top Contributors

[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/0)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/0)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/1)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/1)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/2)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/2)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/3)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/3)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/4)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/4)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/5)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/5)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/6)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/6)[![](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/images/7)](https://sourcerer.io/fame/cuducos/cuducos/flask_simplelogin/links/7)

Add yourself, send a PR!

## How it works

First install it from [PyPI](https://pypi.org/project/flask_simplelogin/).

> `pip install flask_simplelogin`

```python
from flask import Flask
from flask_simplelogin import SimpleLogin

app = Flask(__name__)
SimpleLogin(app)
```

## **That's it!**

Now you have `/login` and `/logout` routes in your application.

The username defaults to `admin` and the password defaults to `secret` (yeah that's not clever, let's see how to change it)


![Login Screen](/login_screen.png)

## Documentation

To visualize changes on the documentation, it's necessary to install some packages and use Sphinx.

```console
$ pip install -r docs/requirements.txt
$ sphinx-build docs docs/build
```

After that, access: `docs/build/index.html`.