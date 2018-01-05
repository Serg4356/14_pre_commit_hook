# Quadratic Equations Solver

Programm contains function which solves quadratic equations. Also you can find unit-test module, and pre-commit hook file, which you can use to ran test automatically before commit changes in your repository.

# Quick Start

## quadratic_equation.py

Example of module usage:

```python
from quadratic_equation import get_roots


print(get_roots(1,-2,1)) # Output: 1

```

## pre-commit

pre-commit file contains Shell script which runs unit-tests before commiting. To use it correctly put it into .git\hooks folder in your project catalog. Besides open it in any text-viewer and change values of these variables:

```bash
powerShellPath="c:/Windows/System32/WindowsPowerShell/v1.0/powershell.exe" # Path to powershell
pythonExePath="C:\ProgramData\Anaconda3\python.exe" # Path to python executable file
testUnitPath="G:\devman\14_pre_commit_hook\tests.py" # Path to your unit-tests file
```


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
