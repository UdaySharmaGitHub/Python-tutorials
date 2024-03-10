## Data Conversion
- The process of converting numeric data from **one type to another** is called as ***type conversion***.
- To convert from **integer to float**, we use ***float()*** function.
- To convert from ***integer to complex***, we use the ***complex()*** function.
- You can convert from **one type to another** with the ***int()***, ***float()***, and ***complex()*** methods:

Example:
```bash
num1 = -25
num2 = float(num1)
num3 = complex(num1)
print(num,type(x))
print(num,type(x))
```
output:-
```bash
-25.0
<class 'float'>
(-25+0j)
<class 'complex'>
```

- To convert from ***float to integer***, we use ***int()*** function. **int()** function **rounds of** the given number to the **nearest integer value.**
- To convert from **float to complex**, we use the ***complex()*** function.

Example:
```bash
x = 1    # int
y = 2.8  # float
z = 1j   # complex
#convert from int to float:
a = float(x)
#convert from float to int:
b = int(y)
#convert from int to complex:
c = complex(x)
print(a)
print(b)
print(c)
print(type(a))
print(type(b))
print(type(c))
```
output:-
```bash
1.0
2
(1+0j)
<class 'float'>
<class 'int'>
<class 'complex'>
```
### Type Casting
- Similar to type conversion, type casting is done when we want to specify a type on a variable. 
### Specify a Variable Type
- There may be times when you want to specify a type on to a variable. This can be done with casting. Python is an object-orientated language, and as such it uses classes to define data types, including its primitive types.
- Casting in python is therefore done using constructor functions:

- int() - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number)
- float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)
- str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

Example:- 1
```bash
str1 = "7"          
str2 = "3.142"
str3 = "13"
num1 = 29
num2 = 6.67
print(int(str1))
print(float(str2))
print(float(str3))
print(str(num1))
print(str(num2))
```
output:- 
```bash
7
3.142
13.0
29
6.67
```