## 🧩 1. Basic Syntax

Writing and running Python code (.py files)

Indentation (Python uses indentation instead of braces {})

Comments (# single-line, ''' multi-line ''')
```
# This is a comment
print("Hello, Python!")  # Prints a message
```

## 🔢 2. Data Types

Numbers: int, float, complex

Strings: 'hello', "world"

Booleans: True, False

NoneType: None
```
x = 10          # int
y = 3.14        # float
name = "Alice"  # string
is_active = True  # boolean
none_value = None  # NoneType

print(type(x), type(y), type(name), type(is_active), type(none_value))
```
## 📦 3. Variables

Declaring variables (x = 10)

Dynamic typing (no need to declare data type)

Variable naming rules
```
a = 5
b = "Python"
a, b = b, a  # Swap values
print(a, b)
```

## 🧮 4. Operators

Arithmetic: +, -, *, /, //, %, **

Comparison: ==, !=, >, <, >=, <=

Logical: and, or, not

Assignment: =, +=, -=, etc.
```
x = 10
y = 3

print(x + y)   # Addition
print(x // y)  # Floor division
print(x ** y)  # Exponentiation
print(x > y and y < 5)  # Logical AND
```

## 📚 5. Data Structures

List: [1, 2, 3]

Tuple: (1, 2, 3)

Set: {1, 2, 3}

Dictionary: {'key': 'value'}
```
# List
fruits = ["apple", "banana", "cherry"]

# Tuple
colors = ("red", "green", "blue")

# Set
unique_numbers = {1, 2, 3, 3}

# Dictionary
person = {"name": "John", "age": 25}

print(fruits, colors, unique_numbers, person)
```

## 🔁 6. Control Flow

If-Else statements

Loops: for, while

Break, continue, pass
```
x = 5

if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")

for i in range(3):
    print("Loop:", i)

while x > 0:
    print("Counting down:", x)
    x -= 1
```

## 🧰 7. Functions

Defining functions with def

Parameters and return values

Default and keyword arguments

lambda (anonymous functions)
```
x = 5

def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))

# Lambda function
square = lambda n: n * n
print(square(4))

```

## 🧱 8. Modules and Packages

Importing modules (import math)

Using built-in libraries

Creating your own modules
```
import math

print(math.sqrt(16))
print(math.pi)
```

## 🧵 9. Input and Output

input() for user input

print() for output

Reading/Writing files with open()
```
# name = input("Enter your name: ")  # Uncomment to use input
# print("Hello,", name)

with open("example.txt", "w") as file:
    file.write("Python is fun!")

with open("example.txt", "r") as file:
    print(file.read())
```

## ⚠️ 10. Error Handling

try, except, finally

Raising exceptions with raise
```
try:
    result = 10 / 0
except ZeroDivisionError:
    print("You can’t divide by zero!")
finally:
    print("Done handling errors.")
```

## 🧑‍🏫 11. Object-Oriented Programming (OOP)

Classes and objects

Methods and attributes

Inheritance

Encapsulation and polymorphism
```
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} says Woof!")

my_dog = Dog("Buddy")
my_dog.bark()
```

## 🧩 12. Miscellaneous

List comprehensions

Iterators and generators

Decorators

Virtual environments (venv)

Working with libraries (pip install)
```
# List comprehension
squares = [x**2 for x in range(5)]
print(squares)

# Generator
def countdown(n):
    while n > 0:
        yield n
        n -= 1

for num in countdown(3):
    print(num)
```
