# Git-Hooks
Config for setting up pre-commit hooks for your projects/teams.

A python package called pre-commit to create and use pre-commit hooks and the same could be used for projects of any tech stack

To setup install the package

- 'pip install pre-commit'
- Create a .pre-commit-config.yaml file within your project.
This file contains the pre-commit hooks you want to run every time before you commit(shared above)
- 'pre-commit install'
- When committing the code, you can see the hook being triggered.
- It could also be run as 'pre-commit run --all-files'

References:

1. https://githooks.com/
2. https://github.com/pre-commit/pre-commit-hooks
2. https://towardsdatascience.com/pre-commit-hooks-you-must-know-ff247f5feb7e
