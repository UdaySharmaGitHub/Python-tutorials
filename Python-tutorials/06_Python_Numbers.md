## Python Numbers
In Python, numbers are of the following data types:
- ***int***
- ***float***
- ***complex***

Variables of numeric types are created when you assign a value to them:
- To verify the type of any object in Python, use the type() function:
```bash
x = 7   # int
y = 3.14  # float
z = 2+1j   # complex
print(type(x))
print(type(y))
print(type(z))
```
output:
```bash
<class 'int'>
<class 'float'>
<class 'complex'>
```
### Int
- Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.
- Or integer of any length. int should not be a decimal or a fraction.
```bash
int1 = -23456
int2 = 0
int3 = 100548
print(type(int1))
print(type(int2))
print(type(int3))
```
output:-
```bash
<class 'int'>
<class 'int'>
<class 'int'>
```
### Float
- Float, or "floating point number" is a number, positive or negative, containing one or more decimals.
```bash
x = 1.10            #decimal number    
y = 1.0             #decimal number
z = -35.59          #decimal number
flt1 = -8.35245     #decimal number
flt2 = 0.000001     #decimal number
print(type(flt1))
print(type(flt2))
print(type(x))
print(type(y))
print(type(z))
```
output:-
```bash
<class 'float'>
<class 'float'>
<class 'float'>
<class 'float'>
<class 'float'>
```
- Float can also be scientific numbers with an "e" to indicate the power of 10.

```bash
flt1 = 2.6E44       #exponential number
flt2 = -6.022e23    #exponential number
x = 10e9            #exponential number 
y = 7E4             #exponential number
z = -10.5e100       #exponential number
print(type(flt1))
print(type(flt2))
print(type(x))
print(type(y))
print(type(z))
```

### Complex
- Complex numbers are a combination of real and imaginary number. They are of the form a + bj, where a is the real part and bj is the imaginary part.
- Complex numbers are written with a "j" as the imaginary part:
```bash
x = 10+7j
y = 14j
z = -25j
cmplx1 = -(3 + 7j)
cmplx2 = -4.1j
print(type(cmplx1))
print(type(cmplx2))
print(type(x))
print(type(y))
print(type(z))
```
output:-
```bash
<class 'complex'>
<class 'complex'>
<class 'complex'>
<class 'complex'>
<class 'complex'>
```
