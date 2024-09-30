# Functions/Methods

- User-defined function:  We can create our own functions based on our requirements.
````md magic-move {lines: true}
```python
# Functions without parameters
def say_hello():
    print("Hello!")

# Functions with parameters
def add_numbers(num1, num2):
    print(f"{num1} + {num2} = {num1 + num2}")

# Functions with return values
def square(num):
    return num ** 2

say_hello() # Output: Hello!
add_numbers(1, 2) # Output: 1 + 2 = 3
print(square(4)) # Output: 16
```

```python
# Functions without parameters
def say_hello():
    print("Hello!")

# Functions with parameters
def add_numbers(num1, num2):
    print(f"{num1} + {num2} = {num1 + num2}")

# Functions with return values
def square(num):
    return num ** 2

say_hello() # Output: Hello!
add_numbers(1, 2) # Output: 1 + 2 = 3
x = square(4)
print(x) # Output: 16
```
````
