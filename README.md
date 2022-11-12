# Python project template
A simple template to easily start a Python project with a clean architecture.

- [`poetry`](https://github.com/python-poetry/poetry) for dependency management
- [`pylint`](https://github.com/PyCQA/pylint/) for static code analysis
- [`mypy`](https://github.com/python/mypy) for static type checks
- [`black`](https://github.com/psf/black) as the code formatter
  - With [`isort`](https://github.com/PyCQA/isort) profile for import ordering
- [`pre-commit`](https://github.com/pre-commit/pre-commit) hooks to enforce clean commits with the above tools
  - Versions [synced with `poetry.lock`](https://github.com/floatingpurr/sync_with_poetry)
- [`dependabot`](https://github.com/dependabot) for automated dependency updates

## Installation

```sh
# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
poetry install

# Setup the pre-commit hook
pre-commit install
```

For the best experience you can also configure your IDE to directly
 show warnings and format on save.

> Look at the Python section of [my VSCode settings](https://github.com/RezaRahemtola/dotfiles/blob/main/vscode/settings.json)
>  for example 😉