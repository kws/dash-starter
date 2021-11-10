# Plotly Dash on Heroku

A starter template for running [Plotly Dash][dash] on Heroku.

## Quick start

[Create an Heroku][[heroku-signup] account if you don't already have one,
and click this button to deploy:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Develop

You need Python > 3.8 and Poetry to run locally.

We use [Poetry][poetry] for dependency management. Once you have
working python version installed, installing Poetry should be as easy as following
the steps on [this page][poetry-install].

However, it's not always that easy. If those steps don't work, download the installer
from [this link][poetry-script]. Find your downloaded file, and the launch it
by running `python install-poetry.py` where `install-poetry.py` is the name of the
downloaded file.

Now, install the dependencies with:

```
poetry install
```

and start the development server

```
poetry run python app.py
```

[dash]: https://dash.plotly.com/installation

[poetry]: https://python-poetry.org/
[poetry-install]: https://python-poetry.org/docs/master/#installation
[poetry-script]: https://raw.githubusercontent.com/python-poetry/poetry/master/install-poetry.py

[heroku-signup]: https://signup.heroku.com/
