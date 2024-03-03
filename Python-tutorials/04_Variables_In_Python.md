## Python Variables
***
### Variables
- Variables are containers for storing data values.
- Variables are containers that store information that can be manipulated and referenced later by the programmer within the code.
- In python, the programmer does not need to declare the variable type explicitly, we just need to assign the value to the variable.
#### Get the Type
You can get the data type of a variable with the type() function.
Example:-
```bash
a=898             #type int
b=415.23         #type float
c="uday sharma"  #type str
d='g'           #type str
print(type(a))
print(type(b))
print(type(c))
print(type(d))
```
output:-
```bash
<class 'int'>
<class 'float'>
<class 'str'>
<class 'str'>
```

### Variable Names
A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- A variable name cannot be any of the Python keywords.
```bash
# Valid Variavle name
myvar = "Uday"
my_var = "Uday"
_my_var = "Uday"
myVar = "Uday"
MYVAR = "Uday"
myvar2 = "Uday"

#  Invalid Varible Name
2myvar = "Uday"
$myvar = "Uday"
my-var = "Uday"
my var = "Uday"
```

### Multi Words Variable Names
- Variable names with more than one word can be difficult to read.
- There are several techniques you can use to make them more readable:
#### Camel Case
- Each word, except the first, starts with a capital letter:
```bash
myVariableName = "Uday"
```
#### Pascal Case
- Each word starts with a capital letter:
```bash
MyVariableName = "Uday"
```
#### Snake Case
- Each word is separated by an underscore character:
```bash
my_variable_name = "Uday"
```
