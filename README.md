# Week 6 Assignment - Handling Errors with try / except

- `safe_tools.py` - three safe functions (`safe_divide`, `safe_number`, `get_field`) that catch specific errors instead of crashing.
- `README.md` - this file: the assignment title, a description of each file, and the answer below.

## Why can the `if` check not catch `abc` on its own?

An `if` check can only compare a value that already exists, but `int("abc")` fails at the moment of conversion, before there is any number for the `if` to test. The program crashes with a `ValueError` first, so only `try` / `except` can catch it.