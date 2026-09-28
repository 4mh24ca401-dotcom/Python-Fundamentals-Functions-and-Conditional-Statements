# Python Fundamentals: Functions and Conditional Statements

This repository contains an annotated follow-along guide for learning core Python concepts. It covers everything from defining basic functions and writing clean code to using comparison operators and conditional logic (`if`/`elif`/`else`).

## 📚 Table of Contents

1.  [Defining Functions and Returning Values](#1-defining-functions-and-returning-values)
2.  [Writing Clean Code](#2-writing-clean-code)
3.  [Using Comments to Scaffold Code](#3-using-comments-to-scaffold-code)
4.  [Making Comparisons Using Operators](#4-making-comparisons-using-operators)
5.  [Using If/Elif/Else Statements](#5-using-ifelifelse-statements)

---

## 1. Defining Functions and Returning Values

This section introduces the basics of functions in Python. It demonstrates how to:
*   Use built-in functions like `print()`, `type()`, and `str()`.
*   Define custom functions using the `def` keyword.
*   Pass arguments (parameters) to functions.
*   Return values from functions using the `return` statement.

**Examples include:**
*   A `greeting()` function that prints a welcome message.
*   An `area_triangle()` function that calculates and returns the area of a triangle.
*   A `get_seconds()` function that converts hours, minutes, and seconds into total seconds.

## 2. Writing Clean Code

This section focuses on the principle of **DRY (Don't Repeat Yourself)**. It shows how to refactor repetitive code into reusable functions.

**Key Comparison:**
*   **Before:** Code that calculates a "lucky number" is written twice for two different people.
*   **After:** A `lucky_number()` function is defined, making the code cleaner, easier to read, and simpler to maintain.

It also includes a factorial calculator example, contrasting a script-style loop with a reusable `factorial()` function.

## 3. Using Comments to Scaffold Code

This section demonstrates how to use comments and docstrings to plan and document your code.

**Example:**
*   A `seed_calculator()` function is presented with a detailed docstring explaining its parameters and return value.
*   Inline comments are used to explain each step of the calculation (e.g., calculating fountain area, total area, grass area, and seed amount).

## 4. Making Comparisons Using Operators

This section covers Python's comparison and logical operators.

**Operators covered:**
*   **Comparison:** `>`, `<`, `==`, `!=`
*   **Logical:** `and`, `or`, `not`

**Examples include:**
*   Comparing numbers and strings.
*   Understanding that strings are compared alphabetically.
*   Using `and` (both sides must be true), `or` (either side can be true), and `not` (reverses the boolean).

## 5. Using If/Elif/Else Statements

This section explains how to control the flow of a program using conditional statements.

**Examples include:**
*   A `hint_username()` function that checks if a username is too short, too long, or valid.
*   An `is_even()` function that uses the modulo operator (`%`) to check if a number is even.

---

## 🚀 How to Use This Notebook

1.  **Clone the repository** or download the `.ipynb` file.
2.  **Open the file** in Jupyter Notebook, JupyterLab, or Google Colab.
3.  **Run the cells** sequentially to see the output of each code block.
4.  **Experiment** by modifying the code and observing the results.

## 🛠️ Requirements

*   Python 3.x
*   Jupyter Notebook or Google Colab (optional, but recommended for the `.ipynb` format)

## 📝 License

This project is open-source and available for educational purposes. 
