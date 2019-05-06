# Quadratic Equations Solver

Programm contains function which solves quadratic equations. Also you can find unit-test module, and pre-commit hook file, which you can use to run test automatically before commit changes in your repository.

# Quick Start

## quadratic_equation.py

Example of module usage:

```python
from quadratic_equation import get_roots


print(get_roots(1,-2,1)) # Output: 1

```

## pre-commit

pre-commit file contains Shell script which runs unit-tests before commiting. To use it correctly put it into .git\hooks folder in your project catalog.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
