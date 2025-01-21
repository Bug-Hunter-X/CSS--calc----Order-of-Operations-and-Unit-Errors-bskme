# CSS `calc()` Gotchas

This repository demonstrates a common error when using the `calc()` function in CSS: unexpected results due to the order of operations and inconsistent units.

## The Bug

The `calc()` function in CSS follows standard mathematical order of operations (PEMDAS/BODMAS). If you don't use parentheses correctly, the calculation might not produce the result you intend. Inconsistent use of units (e.g., mixing pixels and percentages) also leads to errors.  See `bug.css` for examples of such problems.

## The Solution

Always use parentheses to explicitly define the order of operations in `calc()` expressions. Ensure that you use consistent units throughout your calculations.  The corrected code is in `bugSolution.css`.