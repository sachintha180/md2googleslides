---
# Introduction to Python Programming Beginners' Course - Week 6

## Using Loops
---

# Lesson Objectives

1. Understand the basics of `while` loops and how they repeat actions.
2. Learn how to use `for` loops to go through a list of items.
3. Practice simple programs that use loops to repeat actions.
4. Create a basic loop pattern for a program.
5. Complete a mini-project: **Number Guessing Game**.

---

# What is a `while` Loop? Section 1 of 4

---

# Understanding `while` loops

- A **`while` loop** repeats code as long as a condition is **True**.
- **Example**:
  ```python
  count = 1
  while count <= 3:
      print("Hello!")
      count += 1
  ```
- The loop stops when `count` becomes greater than 3.

---

# How to control loops

- Use `break` to **stop** a loop early.
- Use `continue` to **skip** the rest of the code in the loop and start the next round.
- **Example**:
  ```python
  count = 1
  while count <= 5:
      if count == 3:
          break  # Stops the loop at 3
      print(count)
      count += 1
  ```

---

# Important tip: Avoiding infinite loops

- Ensure that your loop has a way to **stop**:

  ```python
  while True:
      print("This runs forever!")  # Avoid this!
  ```

- Always check that the loop condition will become **False** at some point.

---

# Quick Exercise 1 of 4 Write a `while` loop that prints "Good job!" 3 times.

---

# Introduction to `for` Loops Section 2 of 4

---

# What is a `for` loop?

- A **`for` loop** repeats code for each item in a list or range.
- **Example**:
  ```python
  for i in range(3):
      print("Python is fun!")
  ```
- The code prints "Python is fun!" 3 times.

---

# Using `range()` with `for` loops

- `range()` creates a series of numbers:
  - `range(5)` → `0, 1, 2, 3, 4`
  - `range(1, 4)` → `1, 2, 3`
- Used to control how many times the loop runs.

---

# Looping through a list

- **Example**:
  ```python
  colors = ["red", "green", "blue"]
  for color in colors:
      print(color)
  ```
- Each loop goes through one item in `colors` and prints it.

---

# Quick Exercise 2 of 4 Write a `for` loop that prints each letter in "HELLO".

---

# Creating Simple Patterns with Loops Section 3 of 4

---

# Repeating patterns with loops

- You can use loops to create patterns:
  ```python
  for i in range(1, 4):
      print("Loop number", i)
  ```
- This prints:
  ```
  Loop number 1
  Loop number 2
  Loop number 3
  ```

---

# Adding user input with loops

- **Example**:
  ```python
  repeat = int(input("How many times to say hi? "))
  for i in range(repeat):
      print("Hi!")
  ```
- The loop repeats as many times as the user inputs.

---

# Quick Exercise 3 of 4 Write a `for` loop that asks for a number and prints "Learning is fun!" that many times.

---

# Project: Number Guessing Game Section 4 of 4

---

# Your task: Create a Number Guessing Game

- Write a program that:
  - Chooses a number between 1 and 10.
  - Asks the user to guess the number.
  - Uses a `while` loop to check if the guess is correct.
  - Tells the user if they guessed correctly or should try again.

---

# Example: Number Guessing Game output

```python
Guess a number between 1 and 10: 5
Too low, try again!
Guess a number between 1 and 10: 8
Too high, try again!
Guess a number between 1 and 10: 7
You got it!
```

**Hint**: Use `random.randint()` to pick the number.

Once completed, save and share your code as `<name>_6.py`.

---

# Introduction to Python Programming Beginners' Course - Week 6

## Completed
