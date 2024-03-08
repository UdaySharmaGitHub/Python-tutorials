## Python Data Types
***
### Data Types
- Data type specifies the type of value a variable requires to do various operations without causing an error. By default, python provides the following built-in data types:
### Built-in Data Types
- In programming, data type is an important concept.
- Variables can store data of different types, and different types can do different things.
- Python has the following data types built-in by default, in these categories:

|Built-in Data types| Types     |
| :--------         | :------- |
| `Text Type:      `| `str` | 
| `Numeric Types:  `| `int, float, complex` | 
| `Sequence Types: `| `list, tuple, range` | 
| `Mapping Type:   `| `dict` |
| `Set Types:	   `| `set, frozenset` | 
| `Boolean Type:   `| `bool` | 
| `Binary Types:   `| `bytes, bytearray, memoryview` | 
| `None Type:      `| `NoneType` | 

### Setting the Specific Data Type
If you want to specify the data type, you can use the following constructor functions:

### Numeric data: int, float, complex
int: 3, -8, 0
float: 7.349, -9.0, 0.0000001
complex: 6 + 2i
more on numeric data types in the number chapter.
### Text data: str
str: “Hello World!!!”, “Python Programming”
### Boolean data:
Boolean data consists of values True or False.
### Sequenced data:
list, tuple, range

### Setting the Data Type
- In Python, the data type is set when you assign a value to a variable:

|Example                             |Example     |
| :----------------------------------| :------- |
| `x = "Hello World"                `| `str` | 
| `x = 20                           `| `int` | 
| `x = 20.5                         `| `float` | 
| `x = 1j                           `| `complex` |
| `x = ["apple", "banana", "cherry"]`| `list` | 
| `x = ("apple", "banana", "cherry")`| `tuple` | 
| `x = range(6)                     `| `range` | 
| `x = {"name" : "John", "age" : 36}`| `dict` | 
| `x = {"apple", "banana", "cherry"}`| `set` | 
| `x = frozenset({"apple", "banana", "cherry"})`| `frozenset` | 
| `x = True                         `| `bool` | 
| `x = b"Hello"                     `| `bytes` |
| `x = bytearray(5)                 `| `bytearray` | 
| `x = memoryview(bytes(5))         `| `memoryview` | 
| `x = None                         `| `NoneType` | 

### Setting the Specific Data Type
- If you want to specify the data type, you can use the following constructor functions:

|Example                                     |Data Type     |
| :------------------------------------------| :------- |
| `x = str("Hello World")	                `| `str` | 
| `x = int(20)	                            `| `int` | 
| `x = float(20.5)	                        `| `float` |
| `x = complex(1j)	                        `| `complex` | 
| `x = list(("apple", "banana", "cherry"))	`| `list` | 
| `x = tuple(("apple", "banana", "cherry"))	`| `tuple` | 
| `x = range(6)	                            `| `range` | 
| `x = dict(name="John", age=36)	        `| `dict` | 
| `x = set(("apple", "banana", "cherry"))   `| `set` | 
| `x = frozenset(("apple", "banana", "cherry"))`| `frozenset` | 
| `x = bool(5)	                            `| `bool` |
| `x = bytes(5)	                            `| `bytes` | 
| `x = bytearray(5)	                        `| `bytearray` | 
| `x = memoryview(bytes(5))	                `| `memoryview` | 

### list:
-  A list is an ordered collection of data with elements separated by a comma and enclosed within square brackets. Lists are mutable and can be modified after creation.
Example:
```bash
list1 = [8, 2.3, [-4, 5], ["apple", "banana"]]
print(list1)
```
output:
```bash
[8, 2.3, [-4, 5], ['apple', 'banana']]
```

