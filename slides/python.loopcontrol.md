# Loop Control

- Break: The break statement in Python is used to exit a loop prematurely.

- Continue: The continue statement in Python is used to skip the remainder of the code inside a loop for the current iteration only.

- Pass: The pass statement in Python is a null operation.

````md magic-move {lines: true}
```python {*|1|7|2|8|3|8|9|10}
haystack = [
    "hay",
    "needle",
    "hay",
    "hay"
]
for thing in haystack:
    if (thing == "needle"):
        print("Found the needle!")
        break
```
```python {*|1|2|3|4|5}
age = 22
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|2|3|4|5}
age = 21
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|2|3|4|5}
age = 20
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|2|3|4|5}
age = 19
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|2|3|4|5}
age = 18
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|2|3|6|7|8}
age = 17
while True:
    if (age >= 18):
        print(f"{age} is good")
        age -= 1
    else:
        print("Ayo?")
        break
```
```python {*|1|7|2|8|10|7|3|8|10|7|4|8|9|7|5|8|10}
todos = [
    "Wake up",
    "Eat",
    "Touch grass",
    "Code",
]
for todo in todos:
    if (todo == "Touch grass"):
        continue
    print(f"Doing: {todo}")
```
```python {*|1|2|3|6|7}
num = 1
while True:
    if ((num % 2) == 0):
        num += 1
        continue
    print(f"{num} is odd")
    num += 1
```
```python {*|1|2|3|4|5}
num = 2
while True:
    if ((num % 2) == 0):
        num += 1
        continue
    print(f"{num} is odd")
    num += 1
```
```python
num = 3
while True:
    if ((num % 2) == 0):
        num += 1
        continue
    print(f"{num} is odd")
    num += 1
```
```python
animal = []
for animal in animals:

# IndentError
```
```python
def add_numbers(num1, num2):

add_numbers(1, 2)
# IndentError
```
```python
animal = []
for animal in animals:
    pass
def add_numbers(num1, num2):
    pass
add_numbers(1, 2)
# Nothing happens
```
````
