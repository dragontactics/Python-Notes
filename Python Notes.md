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
  - [Comments](#comments)
  - [Assigning Variables](#assigning-variables)
  - [Getting Input](#getting-input)
    - [Casting](#casting)
    - [String Functions](#string-functions)
    - [Arithmetic Operations](#arithmetic-operations)
  - [Comparison Operations](#comparison-operations)
  - [Logical Operators](#logical-operators)
  - [Conditional Statements](#conditional-statements)
  - [Loops](#loops)
    - [While Loops](#while-loops)
    - [For Loops](#for-loops)
  - [Lists](#lists)
  - [Range Function](#range-function)
  - [Tuples](#tuples)
  - [Functions](#functions)
  - [Try Exceptions](#try-exceptions)
  - [Files](#files)
    - [Reading Files](#reading-files)
    - [Writing Files](#writing-files)
    - [Appending Files](#appending-files)
  - [Modules & Pip](#modules--pip)
  - [Classes](#classes)
  - [Objects](#objects)
  - [Inheritance](#inheritance)

---

## **Videos**

- [ ] [Learn Python - Full Course for Beginners [Tutorial]](<https://www.youtube.com/watch?v=rfscVS0vtbw>)
- [ ] [Python for Beginners - Learn Python in 1 Hour](<https://www.youtube.com/watch?v=kqtD5dpn9C8>)
- [ ] [Python Tutorial - Python Full Course for Beginners](<https://www.youtube.com/watch?v=_uQrJ0TkZlc>)
- [ ] [Python Full Course 🐍 -Learn to code today-](<https://www.youtube.com/watch?v=XKHEtdqhLK8>)
- [ ] [Intermediate Python Programming Course](<https://www.youtube.com/watch?v=HGOBQPFzWKo>)
- [ ] [Python for Everybody - Full University Python Course](<https://www.youtube.com/watch?v=8DvywoWv6fI&t=43s>)

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

## Comments

To write comments you use #.

```python
#Comment
```

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

You can add things to a string with variables.

```python
variableName = 'variable'
print("This is a " + variableName)
```

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
- ** (Exponent) or pow(number, exponent)
- % (Modulus)

> Augmented Operations => variableName (operator)= value.
>
> This would evaluate the expression of the variable and the value and replace the variable with the expression's value.

| Functions | Description |
|-|-|
| round(numberVariable) | Returns the number to a integer |
| sqrt(numberVariable) | Returns the square root of the number |
| | |
| | |
| | |

The order of operations is PEMDAS like, but to make sure that the expression is evaluated correctly use parentheses.

---

## Comparison Operations

- \> (greater Than)
- < (Less than)
- <= (Greater than or equal to)
- \>= (Less than or equal to)
- == (Equal to)
- != (Not equal to)

> number < number2

---

## Logical Operators

- and
- or
- not

>Boolean and Boolean

---

## Conditional Statements

There are if statements. To write them do this...

There are elif statements.

```python
if condition:
  ...
elif condition2:
  ...
else:
  ...
```

---

## Loops

### While Loops

Will loop through a set of statements given that the condition is true.

```python
while condition:
  ...
```

### For Loops

```python
listName= [...]
for element in listName:
  ...
```

---

## Lists

A list of elements.

```python
variableName = ["a", "b", "c", ..., "z"] #Make the list with elements
variableName[-1] #z
variableName[-2] #y
variableName[0] = "ab" #changes it to ab
variableName[0:3] #Selects the elements in the range
```

| Functions | Description |
|-|-|
| .insert(index, object) | inserts a new element in a list |
| .remove(index) | removes the element |
| .clear() | removes all elements |
| object in listName | checks if a object is in a list. Returns a boolean. |
| len(listName) | returns the length of the list |
| listName.copy() | Returns a copy the list |

---

## Range Function

This will generate a range of numbers from zero to the given number or between two numbers and a third value that will act as a step.

```python
numbers = range(6) #0, 1, 2, 3, 4, 5
numbers = range(6, 10)#6, 7, 8, 9
numbers = range(5, 10, 2)#5, 7, 9
```

---

## Tuples

Tuples cannot be changed.

```python
numbers = (1, 2, 3, 4, 5, 6, ...)
```

---

## Functions

Functions are a set of statements that are executed when the function is called. You can have parameters.
There is a return statement that can be used to return a value.

```python
def function_name: #All lower case and separated by underscores
  ...
def function_name(parameter1, ...):
  ...
  return ...
  
```

---

## Try Exceptions

Can handle errors so that the program does not crash the program. Will try run the code in the try block and if it fails the program will go to the except block. You can have different statements for different exceptions.

```python
try:
  ...
except:
  ...
except ZeroDivisionError:
  ...
except ValueError:
  ...
```

---

## Files

To access files you have to open the file in python but it is important to close the file when the program is done or the file's use is over.

```python
example_file = open("example.txt","r+") # r+ stands for reading and writing to a file
example_file.close()
```

### Reading Files

```python
example_file = open("example.txt","r") # r stands for read
example_file.readline()
example_file.close()
```

### Writing Files

>Will overwrite things in the file

```python
example_file = open("example.txt","w") # w stands for write
example_file.write()
example_file.close()
```

### Appending Files

>Will NOT overwrite things in the file but will add to the end of the file

```python
example_file = open("example.txt","a") # a stands for append
example_file.close()
```

---

## Modules & Pip

You can make modules so you can use them in your main program later. You can also import other modules. Importing a external modules/libraries will import it into the file.
>[List of python modules (python 3.6.3)](<https://docs.python.org/3/py-modindex.html>)

```python
programs.py
  def functionName():
    print("Its a function")
  ...
```

```python
main.py
  import programs
  programs.functionName()
  ...
```

Pip is a package manager for python. It will install, update and uninstall modules. Python 3 will have pip installed.

External installed modules will be in site-packages.

---

## Classes

Basically, a layout for a object. There are object functions and methods. 

```python
example.py
class Class_Name:
  
  def __init__(self, variable1): # self is just the name of the object
    self.variable1 = variable1
    ...
  
  def function_name(): # can add parameters to the function
  ... # Can change object properties
```

---

## Objects

The result of a filled out class.

```python
from Class_Name import example
object_name = Class_Name("variable")
object_name.function_name
```

---

## Inheritance

Classes can inherit from other classes.

```python
example.py
class Class_Name(Other_Class):

  def new_function_name(): # can add parameters to the function
  ... # Can change object properties
```

---

