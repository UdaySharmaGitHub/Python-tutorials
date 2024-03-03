## Python Comments
***
- A comment is a part of the coding file that the programmer does not want to execute, rather the programmer uses it to either explain a block of code or to avoid the execution of a specific part of code while testing.
- Comments can be used to explain Python code.
- Comments can be used to make the code more readable.
- Comments can be used to prevent execution when testing code.

### Single-Line Comments:
- To write a comment just add a ‘#’ at the start of the line.
Example 1:
```bash
#This is a 'Single-Line Comment'
print("Hi my name is Uday.")
```
Output:
```bash
This is a print statement. 
```
Example 2:
```bash
print("Code with uday !!!") #Printing Code with uday
```
Output:
```bash
Code with uday !!!
```
Example 3:
```bash
print("Python Program")
#print("Python Program")
```
Output:
```bash
Python Program
```

### Multiline Comments
- Python does not really have a syntax for multiline comments.
- To add a multiline comment you could insert a # for each line:
Example 1: The use of ‘#’.
```bash
#This is a comment
#written in
#more than just one line
print("Hello, World!")
if 5>2:
    print("🐍🐍")
else:
    print("🥲🥲")
```
output
```bash
Hello, World!
🐍🐍
```
- Or, not quite as intended, you can use a multiline string.
- Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it:
- The use of multiline string.
Example 2: The use of multiline string.
```bash
"""This is an if-else statement.
It will execute a block of code if a specified condition is true.
If the condition is false then it will execute another block of code."""
p = 7
if (p > 5):
    print("p is greater than 5.")
else:
    print("p is not greater than 5.")
```
Output:
```bash
p is greater than 5.
```
