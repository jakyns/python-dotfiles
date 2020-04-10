# Python Dotfiles

My personal python dotfiles to help making all my python file be consistency
and following pep8 rules.

## Installation

Initiate virtual environment and generate Pipfile and Pipfile.lock by running:

```sh
pipenv lock
```

Install dependencies and get into virtual environment.

```sh
pipenv install && pipenv shell
```

## Usage

```sh
pre-commit install
```

All python files will be automatically reformat and verify before you commit.
