---
# Introduction to Python Programming Beginners' Course - Week 7

## Combining Conditionals and Loops
---

# Lesson Objectives

1. Learn how to use `if` statements within loops to create interactive programs.
2. Understand how nested loops and conditionals work together.
3. Practice creating programs that filter and count specific items.
4. Write simple interactive programs with loops and conditionals.
5. Build a mini-project that applies conditionals and loops.

---

# Using `if` Statements in Loops Section 1 of 4

---

# Why Use `if` in Loops?

- **Loops** help repeat code multiple times.
- **`if` statements** make decisions during each loop iteration.
- Combining them allows for **flexible and interactive programs**.
- Example: Counting only positive numbers in a list.

---

# Example: Positive Number Counter

- **Code snippet**:
```python
numbers = [-3, 7, 1, -5, 9]
for num in numbers:
    if num > 0:
        print(num, "is positive")
```
- **Explanation**:
  - Loops through the list and checks if each number is positive.
  - Prints only positive numbers.

---

# Quick Exercise 1 of 4 Write a loop that prints only even numbers between 1 and 20.

---

# Nested Loops and Conditionals Section 2 of 4

---

# What Are Nested Loops?

- A **nested loop** is a loop inside another loop.
- Useful for checking multiple conditions or working with **2D structures** (e.g., grids).

---

# Example: Nested Loop with Conditions

- **Code snippet**:
```python
for i in range(1, 4):
    for j in range(1, 4):
        if i != j:
            print(i, j)
```
- **Explanation**:
  - The outer loop runs from 1 to 3.
  - The inner loop runs from 1 to 3 for each iteration of the outer loop.
  - Prints combinations where `i` is not equal to `j`.

---

# Quick Exercise 2 of 4 Write a nested loop that prints numbers from 1 to 3 alongside letters A to C.

---

# Filtering and Counting Section 3 of 4

---

# Using Loops for Filtering

- You can use loops and `if` statements to **filter and count items**.
- Example: Count how many words in a list have more than 4 letters.

---

# Example: Word Filter

- **Code snippet**:
```python
words = ["apple", "hat", "banana", "dog"]
count = 0
for word in words:
    if len(word) > 4:
        count += 1
print("Words with more than 4 letters:", count)
```
- **Explanation**:
  - Checks each word's length.
  - Increases the `count` if the condition is met.

---

# Quick Exercise 3 of 4 Create a loop that counts how many numbers in a list are greater than 10.

---

# Interactive Programs with Loops Section 4 of 4

---

# Writing Interactive Programs

- Use loops and `if` statements for **simple interactive tasks**.
- Example: A program that asks a user to guess a number until they get it right.

---

# Example: Number Guessing Game

- **Code snippet**:
```python
secret_number = 5
guess = 0
while guess != secret_number:
    guess = int(input("Guess the number: "))
    if guess < secret_number:
        print("Too low!")
    elif guess > secret_number:
        print("Too high!")
print("You guessed it!")
```
- **Explanation**:
  - Runs until the user guesses the correct number.
  - Gives feedback if the guess is too low or too high.

---

# Quick Exercise 4 of 4 Modify the guessing game to give the user a hint if they are within 2 numbers of the answer.

---

# Build a Simple Quiz Project Section 5 of 5

---

# Your task: Create a Simple Quiz

- Write a program that:
  - Asks the user 3 questions.
  - Uses a loop to check each answer.
  - Keeps a score for correct answers.

---

# Example: Quiz Program

- **Example Output**:
```
Question 1: What is 2 + 2?
Your answer: 4
Correct!

Question 2: What color is the sky?
Your answer: blue
Correct!

Total score: 2/2
```
- **Hint:** Use a `for` loop and `if` statements to check the answers.
- Once completed, save and share your code as `<name>_7.py`.

---

# Introduction to Python Programming Beginners' Course - Week 7

## Completed