---
# Introduction to Python Programming Beginners' Course - Week 3

## Advanced Arithmetic & Data Conversion
---

# Lesson Objectives

1. Master arithmetic operations beyond basic addition, subtraction, multiplication, and division.
2. Convert input values using `int()` and `float()` functions.
3. Use formatted strings for dynamic output.
4. Practice advanced math operations with real-life applications.
5. Create a "Weekly Expense Tracker" incorporating arithmetic operations, input conversion, and formatted output.

---

# Review of Basic Operations Section 1 of 5

---

# Basic Arithmetic Recap

- Quick review of basic arithmetic operators:
  - **Addition**: `+`
  - **Subtraction**: `-`
  - **Multiplication**: `*`
  - **Division**: `/`
- Remember to use variables to store calculation results for later use.

---

# Using Variables in Calculations

- Examples of variable calculations:
  - `total_cost = price + tax`
  - `balance = initial_amount - expense`
  - `total_distance = speed * time`
  - `average = (score1 + score2 + score3) / 3`

```text
CONTAINS IMAGE OF CODE SNIPPETS SHOWING BASIC CALCULATIONS
```

---

# Quick Exercise 1 of 5 Write a program that calculates the total cost of 3 items and prints the result.

---

# Advanced Arithmetic Operators Section 2 of 5

---

# Introducing Floor Division

- **Floor Division** (`//`): Divides and returns the **largest whole number**.
  - Example: `7 // 2` will return `3`
- Useful when we need to discard decimal values in calculations.

---

# Modulus and Exponentiation

- **Modulus** (`%`): Returns the **remainder** after division.
  - Example: `7 % 2` will return `1`
- **Exponentiation** (`**`): Raises a number to a **power**.
  - Example: `2 ** 3` will return `8`

---

# Practical Use of Advanced Operators

- Floor Division can be used to determine the number of items that fit into a container.
- Modulus is helpful for finding out **remainder values**, such as splitting items evenly.
- Exponentiation is often used in mathematical calculations and growth models.

```text
CONTAINS IMAGE OF CODE SNIPPET SHOWING EXAMPLES OF FLOOR DIVISION, MODULUS, AND EXPONENTIATION
```

---

# Quick Exercise 2 of 5 Write a program using modulus to check if a number is even or odd.

---

# Using `input()` with Data Conversion Section 3 of 5

---

# Getting Input as Numbers

- Use `input()` to get values from the user.
- By default, `input()` captures text, but we can **convert** it to a number:
  - Use `int()` for whole numbers
  - Use `float()` for decimal numbers

---

# Converting Input Examples

- Convert user input to perform calculations:
  - `price = float(input("Enter price: "))`
  - `quantity = int(input("Enter quantity: "))`
  - `total = price * quantity`

---

# Practical Conversion Example

- Ask the user for **distance** and **speed**, calculate **time**:
  - `distance = float(input("Enter distance in km: "))`
  - `speed = float(input("Enter speed in km/h: "))`
  - `time = distance / speed`
  - `print(f"Time needed: {time} hours")`

```text
CONTAINS IMAGE OF CODE SNIPPET WITH USER INPUT AND CONVERSION EXAMPLES
```

---

# Quick Exercise 3 of 5 Write a program that asks for two numbers and multiplies them after converting them to integers.

---

# Formatted Strings with `print()` Section 4 of 5

---

# Using f-strings for Clean Output

- **f-strings** allow us to combine text with variables.
  - Example: `print(f"Total cost: {total_cost} dollars")`
- Makes outputs **more readable** and **dynamic**.

---

# Creating Dynamic Sentences

- f-strings make it easy to create sentences with variable data:
  - `name = "Sarah"`
  - `age = 12`
  - `print(f"My name is {name} and I am {age} years old")`

---

# Practical Output Example

- Example of formatted output for expense tracking:
  - `monday_expense = 20`
  - `print(f"On Monday, you spent {monday_expense} dollars.")`

```text
CONTAINS IMAGE OF CODE SNIPPET SHOWING f-STRING EXAMPLES FOR DYNAMIC OUTPUT
```

---

# Quick Exercise 4 of 5 Write a program that asks the user for their name and favorite number, then displays a sentence with both values using an f-string.

---

# Weekly Expense Tracker Section 5 of 5

---

# Your Task: Weekly Expense Tracker

1. **Ask the user** for daily expenses using `input()` and `float()` for each day.
2. Store each day’s expense in a variable (e.g., `monday`, `tuesday`).
3. Calculate the total weekly expense using addition.

---

# Adding Floor Division and Modulus

1. Use **floor division** to find out how many times a specific amount fits into the total (e.g., "How many $20 bills in total expenses?").
2. Use **modulus** to find the remaining balance after dividing by a specific amount.

---

# Example Output: Weekly Expense Tracker

- Expected output after entering daily expenses:
  - **Monday**: $15.50
  - **Tuesday**: $10.75
  - **Total Weekly Expense**: $145.25
  - **$20 Bills Fit In**: 7
  - **Remaining Balance**: $5.25

**Hint:** Use f-strings to format the final output for readability.

Once completed, save and share your code as `<name>_3.py`.

---

# Introduction to Python Programming Beginners' Course - Week 3

## Completed
