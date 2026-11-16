# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

Install the package in editable mode:

```shell
python -m pip install -e .
```

## Run the tests

Run this command and confirm the expected output:

```shell
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```

```text
Hello, Hee!
```

## Send a change

Create a branch from `main`, commit your change, and push the branch. Open a pull request from your branch to `main`.
