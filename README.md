Based on https://mitelman.engineering/blog/automating-python-best-practices-for-a-new-project/

### Requirements

- [pyenv](https://github.com/pyenv/pyenv-installer)
- [poetry](https://python-poetry.org/): `curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python`

### Setup

1. `poetry install`
2. `poetry run pre-commit install`
3. Change project name and author
4. `poetry run pytest --cov=python_template`

### Updating tools

Update pre-commit hooks: `poetry run pre-commit autoupdate`
