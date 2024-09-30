# Data Types
### Non-Primitive Types
- Lists
- Tuples
- Dictionary
- Sets
````md magic-move {lines: true}
```python
x = ["geeks", "for", "geeks"]  # list
x = ("geeks", "for", "geeks")  # tuple
x = {"geeks", "for", "geeks"} # set
x = {
        "name": "Suraj",
        "age": 24
    } # dictionary
```
```python
x = ["geeks", "for", "geeks"]  # list
print(x) # Output: ["geeks", "for", "geeks"]
print(x[1]) # Output: for
print(x[0:2]) # Output: ["geeks", "for"]
print(x[-1]) # Output: geeks
x[0] = "python"
# Output: ["python", "for", "geeks"]
x.append("intro")
# Output: ["python", "for", "geeks", "intro"]
x.pop()
# Output: ["python", "for", "geeks"]
x.remove("for")
# Output: ["python", "geeks"]
```
```python
x = ("geeks", "for", "geeks")  # tuple
print(x) # Output: ("geeks", "for", "geeks")
print(x[1]) # Output: for
print(x[0:2]) # Output: ("geeks", "for")
print(x[-1]) # Output: geeks
list(x)
x[0] = "python"
# Output: ["python", "for", "geeks"]
x.append("intro")
# Output: ["python", "for", "geeks", "intro"]
x.pop()
# Output: ["python", "for", "geeks"]
x.remove("for")
# Output: ["python", "geeks"]
```
```python
x = ("python", "for", "geeks")  # tuple
print(x) # Output: ("python", "for", "geeks")
print(x[1]) # Output: for
print(x[0:2]) # Output: ("python", "for")
print(x[-1]) # Output: geeks
a, b, c = x
print(a) # Output: python
print(b) # Output: for
print(c) # Output: geeks
a, *b = x
print(a) # Output: python
print(b) # Output: ["for", "geeks"]
```
```python
x = {"geeks", "for", "geeks"} # set
print(x) # Output: {"geeks", "for"}
```
```python
x = {
        "name": "Kyle",
        "age": 21,
        "hobbies": [
            "playing games",
            "reading manga",
            "coding in python"
        ]
    } # dictionary

```
```python
print(x["name"]) # Kyle
print(x.get("name")) # Kyle
print(x["age"]) # 21
print(x.get("age")) # 21
print(x["hobbies"])
# [
#     "playing games",
#     "reading manga",
#     "coding in python"
# ]
print(x["hobbies"][0]) # playing games
```
````
