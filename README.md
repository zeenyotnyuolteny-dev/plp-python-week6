
# Week 6 Assignment: Safe Functions

- `safe_tools.py`: Contains safe functions for division, number conversion, and dictionary lookups.

An `if` check alone cannot prevent `int("abc")` from raising a ValueError when the text is converted. Using try/except lets the program catch the error and return "Not a number" instead of crashing.
