# testspace-python

[![Code style: black][black-badge]][black-link]

Library to use Testspace API and client.

## Installation

Install from PyPi

```console
$ pip install testspace-python
```

or locally:

```
$ pip install -e .[code_style,testing]
```

## Testing

Enter created folder then run tests:

```
$ flake8 .
$ black .
$ pytest
```

To use pre-commit:

```
$ git add *
# to apply to staged files
$ pre-commit run
# restage if changes
$ git add *
# to run on commits
$ pre-commit install
$ git commit -m 'Initial commit'
```

[black-badge]: https://img.shields.io/badge/code%20style-black-000000.svg
[black-link]: https://github.com/ambv/black

(package originally created by [python-pkg-cookiecutter](https://github.com/executablebooks/python-pkg-cookiecutter))
