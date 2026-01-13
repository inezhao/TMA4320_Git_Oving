# Simple example of how to use Pytest

This repository contains a simple example of how to use Pytest for testing Python code.

Begin by installing the packages specified in the `pyproject.toml` (or in the `requirements.txt`). Then, activate your virtual environment using
```bash 
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

Run the tests in the `tests` directory using the following command:
```bash
pytest tests/
```

Alternatively, you can run a specific test file:
```bash
pytest tests/test_math_example_simple.py
```

Manage Pytests output options using command-line flags. For example, to see more detailed output, use
```bash
pytest -v tests/
```
or less verbose output with:
```bash
pytest -q tests/
```
Check [Pytest Output Options](https://docs.pytest.org/en/stable/how-to/output.html) for more details.