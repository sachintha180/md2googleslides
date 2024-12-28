---
# Introduction to Python Programming Beginners' Course - Week 5

## Simple Conditionals
---

# Lesson Objectives

1. Understand the basic structure of `if`, `elif`, and `else` statements.
2. Learn how to use comparison operators for decision-making.
3. Apply conditionals to create programs that make decisions.
4. Practice with simple exercises to reinforce conditional logic.
5. Create a **Weather Guide** mini-project to apply learned concepts.

---

# Introducing Conditionals Section 1 of 4

---

# What are conditionals?

- Conditionals are statements that allow your program to make **decisions** based on conditions.
- They let the program execute different code blocks depending on whether a condition is **True** or **False**.
- Commonly used to add **logic** and **branching** to your programs.

---

# Structure of an `if` statement

- The basic `if` statement checks if a condition is **True**:
  ```python
  if condition:
      # Code to run if condition is True
  ```
- **Example**:
  ```python
  age = 15
  if age >= 13:
      print("You are a teenager.")
  ```

---

# Adding `else` and `elif`

- `else` runs if the `if` condition is **False**:
  ```python
  if condition:
      # Code if condition is True
  else:
      # Code if condition is False
  ```
- `elif` allows multiple conditions:
  ```python
  if condition1:
      # Code for condition1
  elif condition2:
      # Code for condition2
  else:
      # Code if none are True
  ```

---

# Quick Exercise 1 of 4 Write a simple program that checks if a number is positive or negative and prints an appropriate message.

---

# Using Comparison Operators Section 2 of 4

---

# What are comparison operators?

- **Comparison operators** are used to compare values and return **True** or **False**:
  - `==` (equal to)
  - `!=` (not equal to)
  - `>` (greater than)
  - `<` (less than)
  - `>=` (greater than or equal to)
  - `<=` (less than or equal to)

---

# Examples of comparison operators

- **Example**:
  ```python
  x = 10
  y = 20

  print(x == y)  # False
  print(x < y)   # True
  ```

- You can use these operators in `if` statements to add logic.

---

# Quick Exercise 2 of 4 Create a program that checks if a number is greater than 100 and prints a message accordingly.

---

# Creating Programs with Conditionals Section 3 of 4

---

# Making decisions in programs

- Use `if`, `elif`, and `else` to guide the program’s flow.
- Example: Checking age categories
  ```python
  age = int(input("Enter your age: "))
  
  if age < 13:
      print("You're a child.")
  elif age < 18:
      print("You're a teenager.")
  else:
      print("You're an adult.")
  ```

- The program responds based on the user's input.

---

# Nested conditionals

- **Nested conditionals** are `if` statements inside other `if` statements:
  ```python
  num = 15

  if num > 10:
      if num % 2 == 0:
          print("The number is even and greater than 10.")
      else:
          print("The number is odd and greater than 10.")
  ```

- Be mindful of indentation to ensure the code is structured properly.

---

# Quick Exercise 3 of 4 Write a program that checks if a number is divisible by both 3 and 5 and prints a special message.

---

# Project: Create a Weather Guide Section 4 of 4

---

# Your task: Create a Weather Guide program

- Write a program that:
  - Takes the temperature as an input.
  - Checks the temperature range and suggests an activity or clothing.
  - Example suggestions:
    - **Below 10°C**: "It's very cold. Wear a coat!"
    - **10°C to 20°C**: "It's chilly. Consider a sweater."
    - **Above 20°C**: "It's warm. Light clothes are fine."

---

# Example: Weather Guide output

```python
temp = int(input("Enter the temperature in °C: "))

if temp < 10:
    print("It's very cold. Wear a coat!")
elif 10 <= temp <= 20:
    print("It's chilly. Consider a sweater.")
else:
    print("It's warm. Light clothes are fine.")
```

**Hint**: Use `elif` for intermediate conditions.

Once completed, save and share your code as `<name>_5.py`.

---

# Introduction to Python Programming Beginners' Course - Week 5

## Completed