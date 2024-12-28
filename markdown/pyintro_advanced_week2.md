---
# Introduction to Python Programming Advanced Course - Week 2

## Error Handling in Python
---

# Lesson Objectives

1. Understand different types of errors in Python.
2. Learn how to use `try`, `except`, `else`, and `finally` blocks.
3. Create and handle custom exceptions.
4. Explore best practices for debugging and handling errors.
5. Develop a project to implement comprehensive error handling.

---

# Types of Errors in Python Section 1 of 4

---

# Common Types of Errors

- **Syntax Errors**:
  - Occur when Python’s syntax rules are violated.
  - Example: `print(\"Hello\"`
- **Runtime Errors**:
  - Occur when a program runs but encounters an operation it cannot execute.
  - Example: Division by zero (`10 / 0`).
- **Logical Errors**:
  - The program runs without crashing but produces incorrect results.
  - Example: Using `+` instead of `*`.

---

# Examples of Errors

- **Syntax Error**:
  ```python
  if True
      print(\"Missing colon\")
  ```
- **Runtime Error**:
  ```python
  my_list = [1, 2, 3]
  print(my_list[5])  # IndexError: list index out of range
  ```
- **Logical Error**:
  ```python
  def average(a, b):
      return a + b / 2  # Missing parentheses: correct is (a + b) / 2
  ```

```text
Include an image showing common error messages in a Python IDE for better visualization.
```

---

# Quick Exercise 1 of 4 Identify and fix the logical error in a simple program that calculates an average

---

# Using Try-Except Blocks Section 2 of 4

---

# What are Try-Except Blocks?

- **`try` block**: Contains code that may cause an error.
- **`except` block**: Contains code that runs if an error occurs.
- Syntax:
  ```python
  try:
      risky_code()
  except ExceptionType:
      handle_error()
  ```

---

# Example of Try-Except

- Handling division by zero:
  ```python
  try:
      result = 10 / 0
  except ZeroDivisionError:
      print(\"Cannot divide by zero!\")
  ```

- This prevents the program from crashing and provides a meaningful message.

---

# The Else and Finally Blocks

- **`else` block**:
  - Runs if the `try` block succeeds without errors.
- **`finally` block**:
  - Runs regardless of what happens in the `try` block, often used for cleanup.
  ```python
  try:
      file = open(\"example.txt\", \"r\")
  except FileNotFoundError:
      print(\"File not found!\")
  else:
      print(\"File opened successfully.\")
  finally:
      file.close()
  ```

```text
Demonstrate the structure of try-except-else-finally with a flowchart for better understanding.
```

---

# Quick Exercise 2 of 4 Create a try-except block to handle user input errors when converting input to an integer

---

# Custom Exceptions in Python Section 3 of 4

---

# Why Use Custom Exceptions?

- **Custom exceptions** make error handling clearer and more specific.
- They help identify specific error conditions relevant to the program.

---

# Defining a Custom Exception

- Example:
  ```python
  class InvalidInputError(Exception):
      pass
  
  def check_input(value):
      if value < 0:
          raise InvalidInputError(\"Input must be non-negative\")
  
  try:
      check_input(-5)
  except InvalidInputError as e:
      print(e)
  ```

```text
Add an example output showing the custom error message.
```

---

# Quick Exercise 3 of 4 Create a custom exception for handling negative numbers in a simple function

---

# Best Practices for Error Handling Section 4 of 4

---

# Error Handling Best Practices

- **Be specific** with `except` blocks: Catch only expected errors.
- **Avoid bare `except:`**: Use specific exceptions for better control.
- **Log errors**: Use Python’s `logging` module to record errors.
- **Use `finally`**: Ensure resources are released properly (e.g., closing files).
- **Keep it user-friendly**: Provide informative messages to guide the user.

---

# Example: Logging Errors

- Using the `logging` module:
  ```python
  import logging
  
  logging.basicConfig(level=logging.ERROR, filename=\"app.log\")
  
  try:
      risky_code()
  except Exception as e:
      logging.error(\"Error occurred: %s\", e)
      print(\"An error occurred, check app.log for details.\")
  ```

```text
Explain how logging can be used for tracking errors over time.
```

---

# Quick Exercise 4 of 4 Modify a program to log an error when a file operation fails

---

# Error Handling Project Section 5 of 5

---

# Project: User Input Error Handler Program

- **Task**:
  - Write a Python program that:
    - Accepts user input and checks for valid data types.
    - Implements `try`, `except`, `else`, and `finally` blocks.
    - Raises custom exceptions for specific conditions (e.g., negative numbers).
- **Steps**:
  - Create functions to take input and validate it.
  - Handle different errors and provide clear messages.
  - Log errors using the `logging` module.

---

# Example output for the project

- **Expected output**:
  ```
  Enter a positive number: -5
  InvalidInputError: Input must be non-negative
  ```
- **Hint**: Use `int()` for type conversion and `try-except` for error catching.
- **Instruction**: Once completed, save and share your code as `error_handler_2.py`.

---

# Introduction to Python Programming Advanced Course - Week 2

## Completed