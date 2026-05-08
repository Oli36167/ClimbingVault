# Contributing

Thank you for contributing to this project.

## Workflow

- Do **not** push directly to the `main` branch.
- Create a feature branch from `develop`:
    -`feature/...` for new functionality
    -`fix/...` for bug fixes
    -`chore/...` for setup/maintenance/etc.
    -`experiment/...` for experiments
- Open a pull request to merge your changes into `develop`.
- `develop` is periodically merged into `main` for stable versions.

## Code Quality

This repository uses automated code quality checks via GitHub Actions.

Before submitting code:

- all automated tests must pass
- pylint must run without unexpected or unreviewed warnings
    - All pylint warnings must either be fixed or explicitly disabled with justification

You can run checks locally before pushing:

```bash
pylint <your_python_files>
pytest
