# Python Project Template with Pre-Commit Hooks, GitHub Actions, and Poetry

This repository serves as a Python project template using **Poetry** for dependency management. It comes pre-configured with **Pre-Commit** hooks, GitHub Actions, and essential tools for maintaining code quality, such as:

- **isort**: for sorting imports
- **flake8**: for checking code style
- **black**: for automatic code formatting
- **pytest**: for testing
- **pytest-cov**: for code coverage reporting

## Requirements

- **Poetry** version 2.1.3 or higher.

## Installation

Follow these steps to get your environment up and running:

1. **Install Poetry** (if you don't have it installed yet):
   - Make sure you have **Poetry** version 2.1.3 or higher installed. You can check your current version with:

     ```bash
     poetry --version
     ```

   - If you need to install or upgrade Poetry, you can do so with the following command:

     ```bash
     curl -sSL https://install.python-poetry.org | python3 -
     ```

2. **Change project_name and authors in pyproject.toml**:

3. **Install project dependencies** using Poetry:

   ```bash
   poetry install

4. **Activate Poetry virtualenv**:

   ```bash
   poetry shell

5. **Initialize Pre-commit**:

   ```bash
   pre-commit install