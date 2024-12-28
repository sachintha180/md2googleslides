---
# Introduction to Python Programming Advanced Course - Week 1

## Functions and Modular Programming
---

# Lesson Objectives

1. Understand what functions are and their role in programming.
2. Learn how to define and call functions with parameters and return values.
3. Differentiate between global and local scope.
4. Comprehend the benefits of modular programming.
5. Create a project using functions to demonstrate their use in math and string operations.

---

# Introduction to Functions Section 1 of 4

---

# What are Functions?

- **Functions** are blocks of code designed to perform a specific task.
- They allow for **reusable code** and can make programs more organized.
- Syntax for defining a function:
  ```python
  def function_name(parameters):
      # code block
      return value
  ```

---

# Benefits of Using Functions

- **Code reusability**: Write once, use multiple times.
- **Modularity**: Split complex problems into smaller, manageable parts.
- **Readability**: Makes code clearer and easier to understand.
- **Debugging**: Easier to find and fix issues.

---

# Defining and Calling Functions

- Example of defining and calling a function:
  ```python
  def greet(name):
      return f\"Hello, {name}!\"
  
  print(greet(\"Alice\"))
  ```

- This will print: `Hello, Alice!`

```text
Include an image of a simple flowchart showing function input, processing, and output.
```

---

# Quick Exercise 1 of 4 Define a function that takes two numbers and returns their sum

---

# Parameters and Return Values Section 2 of 4

---

# Understanding Parameters and Returns

- **Parameters** allow functions to receive input values.
- The `return` statement sends a value back to where the function was called.
- Example:
  ```python
  def add(a, b):
      return a + b
  
  result = add(5, 3)
  print(result)  # Outputs: 8
  ```

---

# Multiple Parameters and Returns

- Functions can have multiple parameters and can return multiple values:
  ```python
  def calculate(a, b):
      return a + b, a - b
  
  sum, difference = calculate(10, 5)
  ```

- `sum` will be `15` and `difference` will be `5`.

---

# Quick Exercise 2 of 4 Create a function that returns the product and division of two numbers

---

# Global and Local Scope Section 3 of 4

---

# What is Scope?

- **Scope** determines where a variable can be accessed.
- **Local variables** exist only within the function where they are defined.
- **Global variables** exist throughout the program.

---

# Example of Scope

- Local vs. global variable example:
  ```python
  x = 10  # Global variable
  
  def show_scope():
      x = 5  # Local variable
      print(x)  # Prints 5
  
  show_scope()
  print(x)  # Prints 10
  ```

```text
Include a diagram showing the difference between global and local variable scopes.
```

---

# Quick Exercise 3 of 4 Create a program using both global and local variables and observe their behaviors

---

# Modular Programming and Its Purpose Section 4 of 4

---

# What is Modular Programming?

- **Modular programming** involves breaking a program into separate modules or functions.
- Benefits include:
  - **Better organization**: Code is easier to read and manage.
  - **Reusability**: Functions can be reused across projects.
  - **Simplified debugging**: Easier to isolate and fix errors.

---

# Example of Modular Programming

- Simple example:
  ```python
  def calculate_area(length, width):
      return length * width
  
  def display_area(length, width):
      print(f\"The area is {calculate_area(length, width)} sq units\")

  display_area(5, 10)
  ```

```text
Highlight the use of function calls within other functions as a key aspect of modular programming.
```

---

# Quick Exercise 4 of 4 Write a program that calculates the area and perimeter of a rectangle using separate functions

---

# Functions Project Section 5 of 5

---

# Project: Create a Math and String Operation Program

- **Task**:
  - Write a Python program that includes multiple functions to:
    - Add, subtract, and multiply numbers.
    - Reverse a string and count vowels.
  - Demonstrate the use of global and local scopes.
- **Steps**:
  - Define functions for each operation.
  - Include a function that calls the math and string operations.
  - Display results with clear labels.

---

# Example output for the project

- **Expected output**:
  ```
  Sum: 15
  Product: 50
  Reversed String: "gnimmargorP"
  Vowel Count: 3
  ```
- **Hint**: Use `len()` for counting and loops for string reversal.
- **Instruction**: Once completed, save and share your code as `functions_project_1.py`.

---

# Introduction to Python Programming Advanced Course - Week 1

## Completed