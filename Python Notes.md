# Python Notes

## Table of Contents

- [Python Notes](#python-notes)
  - [Table of Contents](#table-of-contents)
  - [**Videos**](#videos)
  - [Articles](#articles)
  - [What is Python?](#what-is-python)
  - [How to get started with Python?](#how-to-get-started-with-python)
  - [Syntax](#syntax)
  - [Data Types](#data-types)
  - [Assigning Variables](#assigning-variables)
  - [Getting Input](#getting-input)
    - [Casting](#casting)
    - [String Functions](#string-functions)
    - [Arithmetic Operations](#arithmetic-operations)
  - [Libraries](#libraries)
  - [Frameworks](#frameworks)

---

## **Videos**

- [ ] [Learn Python - Full Course for Beginners [Tutorial]](<https://www.youtube.com/watch?v=rfscVS0vtbw>)
- [ ] [Python for Beginners - Learn Python in 1 Hour](<https://www.youtube.com/watch?v=kqtD5dpn9C8>)
- [ ] [Python Tutorial - Python Full Course for Beginners](<https://www.youtube.com/watch?v=_uQrJ0TkZlc>)
- [ ] [Python Full Course 🐍 -Learn to code today-](<https://www.youtube.com/watch?v=XKHEtdqhLK8>)

## Articles

- [W3 Schools Python](<https://www.w3schools.com/python/default.asp>)

---

## What is Python?

Python is a high-level, interpreted, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically-typed and garbage-collected.

Python supports modules and packages, which encourages program modularity and code reuse.

Python can be for data science, machine learning, web and software development, automate tasks, and conduct data analysis.

---

## How to get started with Python?

Be sure that you have the latest version of python installed. You can use Pycharm or VSCode. Then make a file with a ".py" extension.

---

## Syntax

- You do not need semicolons.
- It is important to indent
- It is case-sensitive

---

## Data Types

> Note: Because they are dynamically-typed, you do not really need to worry about declaring them in the program but it is possible that you can run into an error related to typing so casting is important. Also they are all objects.

| Types | Categories | Example |
| - | - | - |
| Text | str | ```"Hello"``` |
| Sequence | int, float, complex | ```20, 20.5, 1j``` |
| Numeric | list, tuple, range | ```["apple", "banana", "cherry"], ("apple", "banana", "cherry"), range(6)``` |
| Mapping | dict | ```{"name" : "John", "age" : 36}``` |
| Set | set, frozenset | ```{"apple", "banana", "cherry"}, frozenset({"apple", "banana", "cherry"})``` |
| Boolean | bool | ```True``` |
| Binary | bytes, bytearray, memoryview | ```b"Hello", bytearray(5), memoryview(bytes(5))``` |
| None | Nonetype | ```None``` |

> To check the type you ```type(variableName)```.

---

## Assigning Variables

```python
variableName = 'variableValue'
```

---

## Getting Input

```python
input("Filler Text: ")
```

You can assign the input to a variable.

---

### Casting

```python
int("291")
float("29.1")
bool("True")
str(123)
```

---

### String Functions

| Functions  | Description |
| - | - |
| ```"a" in "away"```| Finds out if a string is in a string. Returns True. |
| | |
| | |
| | |
| | |
| | |
| | |
| | |

---

### Arithmetic Operations

- \+ (Addition)
- \- (Subtraction)
- / (Division) [This will return a floating point number]
  - // (Division) [This will return a integer number]
- \* (Multiplication)
- ** (Exponent)
- % (Modulus)

> Augmented Operations => variableName (operator)= value.
>
> This would evaluate the expression of the variable and the value and replace the variable with the expression's value.

---

## Libraries

---

## Frameworks

---
