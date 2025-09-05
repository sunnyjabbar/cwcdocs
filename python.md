
### Data Types

```python
# String
name = "John Smith"

# Integer
age = 50

# Floating Point Number
pi = 3.14159

# String Concatenation
"Hello " + "John"
#becomes "Hello John"

# Converting Data Types
int_num = 100
float_num = float(int_num)
print(float_num) # result is 100.0

# Checking Data Types
pi = 3.14159
type(pi) #result is float
```

### Print function
```python
# literal string
"This is a literal string"

forename = "John"
surname = "Smith"

# print function
print("My name is " + forename + " " + surname)

# print f-string
# enclose variables in curly brackets
print(f"My name is {forename} {surname}")
```

### Input Function
```python
# new line character
\n

# input statement
Input("What's your name?\n")
```

### Operators
```python
# Arithmetic Operators
10 + 20 # add
20 - 10 # subtract
10 * 20 # multiply
20 / 10 # divide

# Assignment Operator
name = forename + surname

# Comparison Operator
name == forename 
grade > 90
grade >= 90
grade < 90
grade <= 90
```

### IF Statement
```python
# if statement
if condition == true:
	print("condition is true")

# if else statement
if condition == true:
	print("condition is true")
else:
	print("conditon is false")

# elif statement
if condition == true:
	print("condition is true")
elif condition2 == true:
	print("conditon2 is true")
else:
	print("conditon is false")

# Example
if grade == 100:
	print("fantastic full marks")
elif grade > 90 and < 100:
	print("excellent grade 8")
elif grade > 80 and < 90:
	print("passed")
else:
	print("bad luck, better luck next time")
```