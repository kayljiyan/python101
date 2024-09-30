# Variables

<div class="text-md">
<ul>
- A Python variable name must start with a <strong>letter</strong> or the <strong>underscore</strong> character.
</ul>
<ul>
- A Python variable name <strong>cannot</strong> start with a number.
</ul>
<ul>
- A Python variable name can only contain <strong>alpha-numeric</strong> characters and <strong>underscores</strong> (A-z, 0-9, and _ ).
</ul>
<ul>
- Variable in Python names are <strong>case-sensitive</strong> (name, Name, and NAME are three different variables).
</ul>
<ul>
- The reserved words(keywords) in Python cannot be used to name the variable in Python.
</ul>
</div>

````md magic-move {lines: true}
```python
name = "Kyle" # Valid
_name = "Kyle" # Valid
1name = "Kyle" # Invalid
*name = "Kyle" # Invalid
```
```python
myName = "Kyle" # Valid
my_name = "Kyle" # Valid
name1 = "Kyle" # Valid
my*n@me = "Kyle" # Invalid
```
```python
name = "Kyle"
Name = "Gian"
NAME = "Latina"
print(name) # Kyle
```
```python
name = "Kyle"
Name = "Gian"
NAME = "Latina"
print(Name) # Gian
```
```python
name = "Kyle"
Name = "Gian"
NAME = "Latina"
print(NAME) # Latina
```
```python
name = "Kyle" # Valid
else = "Kyle" # Invalid
```
````
