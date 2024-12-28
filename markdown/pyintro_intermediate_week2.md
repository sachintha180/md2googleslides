---
# Introduction to Python Programming Intermediate Course - Week 2

## Mastering Loop Structures
---

# Lesson Objectives

1. Implement `for` and `while` loops for repetitive tasks.
2. Understand practical usage of loops in programs.
3. Explore industry examples of loops in data processing and game mechanics.
4. Practice exercises involving counting and iterating over lists.
5. Build a "Multiplication Table Generator" as a mini-project.

---

# What are Loops? Section 1 of 5

---

# Introduction to Loops

- **Loops** allow a block of code to be executed **repeatedly**.
- Two main types in Python:
  - **`for` loop**: Repeats for a known number of times.
  - **`while` loop**: Repeats while a condition is true.

---

# Why Use Loops?

- Automates repetitive tasks.
- Used in **data processing** (e.g., reading files).
- Common in **game mechanics** for iterating over game objects.

```text
CONTAINS IMAGE OF GAME LOOP ILLUSTRATION OR SIMPLE FLOW DIAGRAM
```

---

# Quick Exercise 1 of 5 Write an algorithm using a loop to print "Hello!" 5 times.

---

# Understanding `for` Loops Section 2 of 5

---

# Structure of a `for` Loop

- Syntax:
  ```python
  for variable in range(5):
      print("Hello!")
  ```
- `range(5)` generates numbers from 0 to 4.

---

# Example: Counting with `for` Loop

```python
for i in range(1, 6):
    print("Count:", i)
```

- This loop prints numbers from 1 to 5.

```text
OUTPUT:
Count: 1
Count: 2
Count: 3
Count: 4
Count: 5
```

---

# Real-World Application of `for` Loops

- **Data processing**: Iterating through a list of items.
- **Web scraping**: Extracting data from web pages.
- **Games**: Repeating actions like animating characters.

```text
CONTAINS IMAGE OF SIMPLE DATA PROCESSING OR AN ANIMATED CHARACTER
```

---

# Quick Exercise 2 of 5 Write a `for` loop that prints numbers 1 to 10.

---

# Understanding `while` Loops Section 3 of 5

---

# Structure of a `while` Loop

- Syntax:
  ```python
  while condition:
      # Code block
  ```
- The loop runs until the **condition becomes false**.

---

# Example: Using a `while` Loop

```python
x = 1
while x <= 5:
    print("Number:", x)
    x += 1
```

- Prints numbers from 1 to 5.

```text
OUTPUT:
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5
```

---

# When to Use `while` Loops

- Ideal for **unknown number of iterations**.
- Useful for **waiting for user input** or handling events.

```text
CONTAINS IMAGE OF AN EVENT-DRIVEN INTERFACE OR A LOADING INDICATOR
```

---

# Quick Exercise 3 of 5 Create a `while` loop that continues until a user inputs "stop".

---

# Using Loops in Practical Tasks Section 4 of 5

---

# Combining Loops with Lists

- Iterate over lists using `for` loops:
  ```python
  items = ["apple", "banana", "cherry"]
  for item in items:
      print(item)
  ```

- **Output**:
  ```
  apple
  banana
  cherry
  ```

---

# Nested Loops

- Loops inside other loops:
  ```python
  for i in range(1, 4):
      for j in range(1, 4):
          print(i, j)
  ```

- **Output**:
  ```
  1 1
  1 2
  1 3
  2 1
  2 2
  2 3
  3 1
  3 2
  3 3
  ```

```text
CONTAINS IMAGE OF NESTED LOOP DIAGRAM
```

---

# Quick Exercise 4 of 5 Write a nested `for` loop to create a 3x3 grid pattern.

---

# Mini-Project: Multiplication Table Section 5 of 5

---

# Your Task: Build a Multiplication Table Generator

- Create a Python program that:
  - Asks the user for a number.
  - Prints the multiplication table up to 10 for that number.
  - Uses a `for` loop for iteration.

```text
TASK STEPS:
- Use `input()` to get user input.
- Implement a `for` loop to print the table.
```

---

# Example Output for Multiplication Table

- **User Input**:
  ```
  Enter a number: 3
  ```

- **Program Output**:
  ```
  3 x 1 = 3
  3 x 2 = 6
  3 x 3 = 9
  3 x 4 = 12
  ...
  3 x 10 = 30
  ```

**Hint**: Use formatted strings for neat output. \
Once completed, save and share your code as `multiplication_table_2.py`.

```text
CONTAINS IMAGE OF A TERMINAL SHOWING A MULTIPLICATION TABLE
```

---

# Introduction to Python Programming Intermediate Course - Week 2

## Completed
