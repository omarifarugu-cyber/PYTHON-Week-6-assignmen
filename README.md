# Week 6 Assignment - Safe Functions

This assignment practices using try/except to handle errors safely.

- `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
- `README.md` - Describes the assignment and explains why an if check cannot catch invalid number conversion.

An `if` check cannot catch `"abc"` when using `int()` because converting `"abc"` to an integer raises a `ValueError`. The `try/except` block catches that error and allows the program to continue running.