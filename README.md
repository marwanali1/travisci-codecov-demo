# Travisci Codecov Demo

[![GitHub](https://img.shields.io/github/license/marwanali1/travisci-codecov-demo?color=g)](https://github.com/marwanali1/travisci-codecov-demo/blob/develop/LICENSE)

Repo for learning how to integrate TravisCI and Codecov with python codebase

### Usage:
Clone the repo: `git clone https://github.com/marwanali1/travisci-codecov-demo.git`

Change into it: `cd travisci-codecov-demo`

Export python path: `export PYTHONPATH=$PWD`  

Install dependencies: `pipenv install`

Start virtual env: `pipenv shell`

Run tests `python3 tests/test_math_functions.py`

Run tests with coverage: `pipenv run coverage run tests/test_math_functions.py`

Leave virtual env: `exit`