---
# Introduction to Python Programming Intermediate Course - Week 1

## Introduction to Python Control Structures
---

# Lesson Objectives

1. Understand `if`, `elif`, and `else` statements.
2. Learn the importance of control structures in software logic.
3. Explore real-world examples and applications.
4. Write simple programs illustrating condition-based actions.
5. Create a "Decision Maker" program as a mini-project.

---

# What are Control Structures? Section 1 of 5

---

# The Basics of Control Structures

- Control structures **determine the flow** of a program based on conditions.
- Allow programs to make **decisions** and execute specific blocks of code.
- Common types include **`if`, `elif`, `else`** statements.

---

# Why Are They Important?

- Essential for making **decisions** in programs.
- Used in web apps for **user interactions** and conditional logic.
- Common in game design to create **responsive gameplay**.

```text
CONTAINS IMAGE OF A DECISION FLOWCHART SHOWING TRUE/FALSE PATHS
```

---

# Example Use Cases in Industry

- **Web development**: Validate user input before submission.
- **Games**: Check conditions to change levels or states.
- **Home automation**: Turn on devices based on conditions.

```text
CONTAINS IMAGE OF A WEB FORM AND SIMPLE GAME LOGIC FLOW
```

---

# Quick Exercise 1 of 5 Write a basic algorithm for deciding what to do if it’s sunny or raining outside.

---

# Understanding `if`, `elif`, and `else` Section 2 of 5

---

# How `if`, `elif`, and `else` Work

1. **`if` statement**: Checks the initial condition.
2. **`elif` statement**: Checks subsequent conditions if the first is false.
3. **`else` statement**: Runs if all conditions are false.

---

# Code Example: Age-Based Checker

```python
age = 17
if age >= 18:
    print("You can vote.")
elif age >= 16:
    print("You can get a driving permit.")
else:
    print("You are too young for these activities.")
```

- This program checks different conditions based on age.

---

# Re. Code Explanation

- **Step-by-step**:
  - The `if` block checks if `age` is 18 or more.
  - If not, `elif` checks if `age` is between 16 and 17.
  - `else` runs if neither condition is met.

```text
CONTAINS IMAGE OF THE OUTPUT "You can get a driving permit."
```

---

# Quick Exercise 2 of 5 Modify the code to print "Child" if age is less than 13.

---

# Real-World Control Structure Applications Section 3 of 5

---

# Applications in Software

- **Login systems**:
  - `if` credentials match, grant access.
- **Game scores**:
  - `if` score reaches a level, trigger bonus round.
- **Smart devices**:
  - `if` motion is detected, turn on lights.

---

# Sample Code: Score Checker

```python
score = 120
if score >= 100:
    print("You leveled up!")
else:
    print("Keep playing to reach the next level.")
```

- Used in many games to evaluate player progress.

```text
CONTAINS IMAGE OF A SIMPLE GAME INTERFACE WITH A "LEVEL UP!" MESSAGE
```

---

# Quick Exercise 3 of 5 Create a program that checks if a number is positive, negative, or zero.

---

# Building Complex Logic Section 4 of 5

---

# Combining `if`, `elif`, and `else`

- Multiple conditions can be handled with `elif`.
- Useful for **tiered decision logic**.

```python
purchase_amount = 250
if purchase_amount > 300:
    print("20% discount applied.")
elif purchase_amount > 200:
    print("10% discount applied.")
else:
    print("No discount.")
```

- This example shows conditional logic for pricing discounts.

---

# Using Nested `if` Statements

- **Nested `if`** allows more detailed logic.
- Example: A weather and temperature guide.

```python
weather = "rainy"
temperature = 18
if weather == "rainy":
    if temperature < 20:
        print("Wear a raincoat and sweater.")
    else:
        print("Wear a raincoat.")
else:
    print("Enjoy the sunshine!")
```

- Combines weather and temperature conditions.

---

# Quick Exercise 4 of 5 Write a nested `if` program to decide if a store is open and if a product is in stock.

---

# Mini-Project: Create a "Decision Maker" Section 5 of 5

---

# Your Task: Create a "Decision Maker"

- Build a program that:
  - Asks the user for a task they need help deciding on.
  - Follows up with a question (e.g., “Is it urgent?”).
  - Provides different advice based on user answers.

```text
TASK STEPS:
- Use `input()` to gather responses.
- Implement `if`, `elif`, and `else` for logic.
```

---

# Example Output for "Decision Maker"

```python
task = input("Enter your task: ")
urgent = input("Is it urgent? (yes/no) ")

if urgent.lower() == "yes":
    print("Complete it immediately.")
elif task.lower() == "study":
    print("Plan and start early.")
else:
    print("Schedule it for later.")
```

**Hint**: Use `.lower()` for uniform input. \
Once completed, save and share your code as `decision_maker_1.py`.

```text
CONTAINS IMAGE OF SHELL OUTPUT SHOWING EXAMPLE DIALOGUE AND RESPONSE
```

---

# Introduction to Python Programming Intermediate Course - Week 1

## Completed
