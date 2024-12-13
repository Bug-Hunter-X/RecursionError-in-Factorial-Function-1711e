# RecursionError in Python Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a base case for negative inputs, resulting in a `RecursionError`.

The `factorial_bug.py` file contains the buggy code, and `factorial_solution.py` provides a corrected version.

The issue arises because the recursive call `factorial(n-1)` continues indefinitely when `n` is negative, exceeding the maximum recursion depth allowed by Python.