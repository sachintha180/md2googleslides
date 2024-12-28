---
# Introduction to Python Programming Beginners' Course - Week 4

## Introducing Strings & Basic String Manipulation
---

# Lesson Objectives

1. Understand what strings are and how they differ from numbers.
2. Learn basic string operations like concatenation and finding length.
3. Use indexing and slicing to extract parts of a string.
4. Format output using `f-strings` and string concatenation.
5. Build a “Fun Fact Generator” using string manipulation techniques.

---

# Understanding Strings Section 1 of 4

---

# What are Strings?

- **Strings** are sequences of characters (letters, numbers, symbols).
- In Python, strings are created by enclosing text in **quotes** (single or double).
  - Example: `"Hello, World!"` or `'Python is fun!'`
- Strings are commonly used for text data.

---

# Examples of Strings

- Words, sentences, and even numbers in quotes are strings:
  - `"apple"`
  - `"This is a sentence."`
  - `"12345"`
- **Important**: `"12345"` is a string, while `12345` is a number (integer).

```text
CONTAINS IMAGE OF CODE SHOWING DIFFERENCES BETWEEN STRINGS AND INTEGERS IN PYTHON
```

---

# Quick Exercise 1 of 4 Write a program that stores your favorite quote in a variable and prints it.

---

# Basic String Operations Section 2 of 4

---

# Concatenating Strings

- **Concatenation** is combining multiple strings together.
  - Example: `greeting = "Hello, " + "world!"` will result in `"Hello, world!"`
- Use `+` to combine strings and create dynamic sentences.

---

# Finding the Length of a String

- Use `len()` to find out how many characters are in a string.
  - Example: `len("Python")` will return `6`.
- This can help you work with strings of various lengths.

---

# Practical Concatenation Example

- Create a full sentence:
  - `name = "Alice"`
  - `activity = "coding"`
  - `print("Hello! My name is " + name + " and I love " + activity + ".")`

```text
CONTAINS IMAGE OF CODE SNIPPET SHOWING CONCATENATION OF NAME AND ACTIVITY
```

---

# Quick Exercise 2 of 4 Write a program that combines your first and last name and prints it.

---

# Indexing and Slicing Section 3 of 4

---

# What is Indexing?

- **Indexing** refers to accessing individual characters in a string.
- Each character has a **position** called an index:
  - First character is at index `0`
  - Second character is at index `1`, and so on.

---

# How to Use Indexing

- Use square brackets `[ ]` to access characters by index:
  - `word = "Python"`
  - `print(word[0])` will print **"P"**
  - `print(word[3])` will print **"h"**

```text
CONTAINS IMAGE OF CODE SHOWING INDEXING EXAMPLES WITH A STRING
```

---

# What is Slicing?

- **Slicing** allows you to extract parts of a string.
- Use the format `string[start:end]` to slice:
  - `word = "Python"`
  - `print(word[0:3])` will display **"Pyt"**

---

# Practical Slicing Example

- Extract initials from a name:
  - `full_name = "Alice Smith"`
  - `initials = full_name[0] + full_name[6]`
  - `print("Initials:", initials)`

```text
CONTAINS IMAGE OF CODE SNIPPET SHOWING SLICING EXAMPLES
```

---

# Quick Exercise 3 of 4 Write a program that asks for your name and prints just the first three letters.

---

# Formatting Strings Section 4 of 4

---

# Using f-strings for Formatting

- **f-strings** make it easy to combine text and variables.
- Use `f` before quotes to include variables in curly braces `{ }`:
  - `name = "Sam"`
  - `print(f"Hello, {name}!")` will print **"Hello, Sam!"**

---

# Concatenation vs. f-strings

- **Concatenation** uses `+` to join strings:
  - `"Hello, " + name`
- **f-strings** allow direct insertion of variables:
  - `f"Hello, {name}"`

```text
CONTAINS IMAGE OF CODE SHOWING EXAMPLES OF CONCATENATION VS. F-STRINGS
```

---

# Practical Example of f-strings

- Create a greeting message:
  - `name = "Jordan"`
  - `age = 12`
  - `print(f"My name is {name} and I am {age} years old.")`

---

# Quick Exercise 4 of 4 Write a program that asks for your pet's name and favorite activity, then prints a sentence using f-strings.

---

# Fun Fact Generator Section 5 of 5

---

# Your Task: Fun Fact Generator

1. Ask the user for three facts about themselves (e.g., favorite color, favorite food, hobby).
2. Combine the facts into a fun sentence using **f-strings** or **concatenation**.

---

# Example Output: Fun Fact Generator

- Example output for the Fun Fact Generator:
  - **Favorite Color**: Blue
  - **Favorite Food**: Pizza
  - **Hobby**: Drawing
  - Output: `"Hi! My favorite color is Blue, I love eating Pizza, and I enjoy Drawing in my free time."`

**Hint:** Use f-strings for an easy way to insert each fact into your sentence.

Once completed, save and share your code as `<name>_4.py`.

---

# Introduction to Python Programming Beginners' Course - Week 4

## Completed
