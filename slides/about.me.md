````md magic-move {lines: true}
```python {*|2-16|17-25|26|8|9}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

me.introduce_yourself()
```
```python {26}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# Hi! I am Kyle.
```
```python {26|11|12}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

me.introduce_program()
```
```python {26}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# I'm from BSIT.
```
```python {26|14|15|16}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

me.introduce_hobbies()
```
```python {26|15|16}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# I love Playing video games
```
```python {26|15|16}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# I love Reading in Mihon
```
```python {26|15|16}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# I love Exploring all things Python
```
```python {26}
# About Me
class Speaker():
    def __init__(self, name, program, hobbies):
        self.name = name
        self.program = program
        self.hobbies = hobbies

    def introduce_yourself(self):
        print(f'Hi! I am {self.name}.')

    def introduce_program(self):
        print(f"I'm from {self.program}.")

    def introduce_hobbies(self):
        for hobby in self.hobbies:
            print(f'I love {hobby}')

me = Speaker("Kyle", "BSIT",
    [
        "Playing video games",
        "Reading in Mihon",
        "Exploring all things Python",
        "Volunteering for events"
    ])

# I love Volunteering for events
```
````
