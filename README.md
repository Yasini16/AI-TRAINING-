✅ Day 1: Introduction to Python

Python is a beginner-friendly, high-level programming language.

Used in AI, data science, web apps, scripting, and automation.

It's interpreted (runs line by line) and uses indentation (no {}).


print("Hello, Python!")


---

✅ Day 2: Basic Operations

Arithmetic: +, -, *, /, //, %, **

Comparison: ==, !=, <, >, <=, >=

Logical: and, or, not

Assignment: =, +=, -=, etc.



---

✅ Day 3: Conditional Statements

Used to perform actions based on conditions.


if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")


---

✅ Day 4: Loops in Python

for loop: Runs for each item in a list/range.

while loop: Runs while a condition is true.


for i in range(5):
    print(i)


---

✅ Day 5: List

Ordered, changeable, allows duplicates.


my_list = [1, 2, 3]
my_list.append(4)


---

✅ Day 6: Tuple

Ordered, unchangeable, allows duplicates.


my_tuple = (1, 2, 3)


---

✅ Day 7: Set

Unordered, no duplicates.


my_set = {1, 2, 3}
my_set.add(4)


---

✅ Day 8: Dictionary

Key-value pairs, very useful in real-world data.


person = {"name": "John", "age": 30}
print(person["name"])


---

✅ Day 9: Dictionary Methods

.get(): Safe way to access values.

.update(): Change or add values.

.keys(), .values(), .items(): Get dictionary content.


person.get("name")


---

✅ Day 10: File Handling

Write to file:


with open("file.txt", "w") as f:
    f.write("Hello")

Read from file:


with open("file.txt", "r") as f:
    print(f.read())


---

✅ Day 11: Errors in Python

Common errors: SyntaxError, TypeError, ZeroDivisionError

Handling:


try:
    x = 10 / 0
except ZeroDivisionError:
    print("Error!")


---

✅ Day 12: OOP, Pillars, Access Modifiers

OOP = Object-Oriented Programming

4 Pillars:

1. Encapsulation – hiding data inside a class


2. Abstraction – showing only needed features


3. Inheritance – reuse from parent class


4. Polymorphism – same function behaves differently



Access Modifiers:

public (default)

_protected (internal use)

__private (hidden)




---

✅ Day 13: Dunder Methods, Threads, AI Basics

Dunder methods: __init__, __str__, __len__, etc.

Thread: Runs multiple tasks at once using threading.

Process: Independent programs using multiprocessing.


AI Math Basics:

Vector = 1D array → [1, 2, 3]

Matrix = 2D → [[1, 2], [3, 4]]

Tensor = Multi-D arrays (used in AI models)
