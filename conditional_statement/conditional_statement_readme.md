# Condtional Statement
Conditional statements, such as if, if-else, and if-elif-else, are used in programming to execute specific blocks of code based on whether a given condition or set of conditions evaluates to True or False. They allow you to control the flow of your program, enabling it to make decisions based on different inputs or variables.

1. ```if``` statement: This is the simplest conditional statement. It executes a block of code only if the specified condition is ```True```. If the condition is ```False```, the code inside the ```if``` block is skipped.


```python
if condition:
    # Code to execute if condition is True

```
#### Example
```python
a = 8
rem = 8 % 2
if rem == 0:
    print("Even number")

```

2. ```if-else``` statement: This statement provides an alternative path if the ```if``` condition evaluates to ```False```. If the condition is ```True```, the code inside the ```if``` block executes; otherwise, the code inside the ```else``` block executes.

```python
if condition:
    # Code to execute if condition is True
else:
    # Code to execute if condition is False
```
#### Example
```python
a = 8
rem = 8 % 2
if rem == 0:
    print("Even number")
else:
    print("Odd number")

```

3. ```if-elif-else``` statement: This statement allows multiple conditions to be checked sequentially. If the first condition is ```False```, it checks the next ```elif``` condition and continues until a ```True``` condition is found. If no conditions are ```True```, the ```else``` block (if provided) executes as a default.

```python
if condition1:
    # Code to execute if condition1 is True
elif condition2:
    # Code to execute if condition2 is True
else:
    # Code to execute if neither condition1 nor condition2 is True
```

```python
a = 8
if a > 0:
    print("Positive number")
elif a < 0:
    print("Negative number")
else:
    print("Number is zero")
```



4. A nested ```if``` condition in Python (or any other programming language) is an ```if``` statement that exists inside another ```if``` statement. It allows you to add multiple levels of decision-making, where a new condition is checked only if the previous condition(s) are met.

### Syntax
In a nested ```if``` structure, the ```if``` block contains another ```if``` statement, and each level of nesting can include its own ```if```, ```else```, or ```elif``` blocks as needed.

```python
if condition1:
    # Code to execute if condition1 is True
    if condition2:
        # Code to execute if both condition1 and condition2 are True
    else:
        # Code to execute if condition1 is True but condition2 is False
else:
    # Code to execute if condition1 is False
```
#### Example

```python
a = 8
rem = 8 % 2
if rem == 0:
    print("Even number")
    if rem > 5:
       print("Even number greater than five")
    else:
        print("Even number less than and equal five")
else:
    print("Odd number")
```
