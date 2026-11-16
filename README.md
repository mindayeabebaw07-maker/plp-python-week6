# PLP Python Week 6 - Safe Tools

## Files
- `safe_tools.py` - Contains safe_divide, safe_number, and get_field functions that use try/except so the program never crashes.

## Why can the if check not catch abc on its own?
An `if` check can only test a value after it already exists, but `int("abc")` crashes during the conversion itself before any `if` can run. Only `try / except ValueError` can catch that crash and let the program continue.
