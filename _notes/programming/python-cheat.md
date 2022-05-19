---
title: Python Cheatsheet
---
## Downloading and installing Python

Python is a [[types-of-languages|high-level]] [[translators|interpreted]] programming language that is supported by most major [[os|operating systems]]. All CIE courses require that students complete their work using a version of Python3 (at the time of writing 3.10 is the most up to date release).

Python can be downloaded and installed from the [official Python website](https://www.python.org/downloads/).

If for any reason you are not able to install Python on your device, there are browser based versions you can use such as [trinket.io](https://trinket.io/python3)

## Creating a variable

## Getting data from the user

## Outputting data to the user

## Making choices

## Counting loop

## Pre-condition loop

## Post-condition loop

Most programming languages include a type of loop known as a `do...while` loop. These loops are similar to `while` loops but have one major difference, the condition is checked at the end of the loop rather than at the beginning of the loop. By making use of this type of loop, the code within the loop is guaranteed to run at least once.

Python does not provide support for these types of loops. In order to build a post-condition loop in python, you need to combine a `while` loop with an `if` statement and a `break` statement.

The following code sample asks a user to enter a new password, the program will only let the user continue if their password is at least 8 characters long

```python
while True: # This sets up an infinite loop
  password = input("Please enter a new password": )

  if len(password) >= 8:
    print("Password updated")
    break # This statement stops the loop from repeating
  else:
    print("Passwords must be at least 8 characters long")
```

## Working with lists