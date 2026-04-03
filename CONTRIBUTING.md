# Contributing to PyAutoLabs

Thank you for your interest in contributing to PyAutoLabs! We welcome contributions from everyone — whether you're fixing a typo, reporting a bug, or adding a new feature.

## How to Contribute

### Reporting Bugs

1. Check existing issues to see if the bug has already been reported.
2. Open a new issue using the **Bug Report** template.
3. Include a minimal reproducible example, your Python/package versions, and the full traceback.

### Suggesting Features

1. Open an issue using the **Feature Request** template.
2. Describe the problem your feature would solve and any proposed solutions.

### Submitting Code

1. **Fork** the repository and create a branch from `main`.
2. Write your changes, following the existing code style.
3. Add or update tests as appropriate.
4. Ensure all tests pass: `pytest`
5. Submit a **Pull Request** with a clear description of what you changed and why.

## Development Setup

```bash
git clone https://github.com/PyAutoLabs/<repo>.git
cd <repo>
pip install -e ".[dev,test]"
pytest
```

## Code Style

- We follow [PEP 8](https://peps.python.org/pep-0008/) with a line length of 120 characters.
- Use type hints where practical.
- Write docstrings for public functions and classes.

## Review Process

- All PRs require at least one review from a maintainer.
- CI must pass before merging.
- We aim to review PRs within one week.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

Open a **Support Question** issue or start a discussion in the relevant repository.
