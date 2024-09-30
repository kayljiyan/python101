# If-Elif-Else

- the if statement evaluates if a condition is true and executes the code block
- the elif statement evaluates if a condition is true and executes the code block
- the else block is executed if none of the conditions were true
````md magic-move {lines: true}
```python {*|1|2|3}
age = 18
if (age >= 18 and age < 60):
    print("You are not a minor")
elif (age < 18):
    print("You are a minor")
else:
    print("You are a senior, dead, or Enrile")
```
```python {*|1|2|4|5}
age = 13
if (age >= 18 and age < 60):
    print("You are not a minor")
elif (age < 18):
    print("You are a minor")
else:
    print("You are a senior, dead, or Enrile")
```
```python {*|1|2|4|6|7}
age = 69
if (age >= 18 and age < 60):
    print("You are not a minor")
elif (age < 18):
    print("You are a minor")
else:
    print("You are a senior, dead, or Enrile")
```
````
