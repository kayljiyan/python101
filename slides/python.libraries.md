# Libraries

- Libraries in Python are collections of modules and packages that provide pre-written code to perform various tasks.
```python
# calculate.py
def add():
    print("Adding")
def subtract():
    print("Subtracting")
def multiply():
    print("Multiplying")
def divide():
    print("Dividing")
```
````md magic-move {lines: true}
```python
# main.py
import calculate

calculate.add() # Output: Adding
```
```python
# main.py
from calculate import add

add() # Output: Adding
```
````
