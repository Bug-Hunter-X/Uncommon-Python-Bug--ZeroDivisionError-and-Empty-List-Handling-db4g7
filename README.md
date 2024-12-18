# Python Code Bug: ZeroDivisionError and Empty List Handling

This repository demonstrates a common yet subtle bug in Python code that involves handling empty lists and lists containing zeros in average calculations.  The original code lacks robust error handling which can lead to a `ZeroDivisionError`.  The solution provides improved error handling and input validation.

## Bug Description

The original `calculate_average` function doesn't explicitly handle the case of an empty list, resulting in a `ZeroDivisionError`. Additionally, while it correctly calculates the average for lists with zeros, the behavior might not be entirely intuitive for all users.  The improved solution addresses both issues.

## How to Reproduce

1. Clone this repository.
2. Run the `bug.py` file. Observe the `ZeroDivisionError` when the function attempts to divide by zero.
3. Run the `bugSolution.py` file to see the improved, more robust version.