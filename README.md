
# Week 6 Assignment: Safe Functions

## Description
This assignment demonstrates how to handle errors in Python using try and except.

## Files

- safe_tools.py: Contains three safe functions for division, number conversion, and dictionary lookup.
- README.md: Provides information about the assignment and explains error handling.

## Why can the if check not catch abc on its own?

An if statement cannot automatically determine whether text can be converted into an integer. The int() function raises a ValueError when it receives invalid text such as "abc". Therefore, try and except are used to catch the error and prevent the program from crashing.

