## Random Number
- Python does not have a random() function to make a random number, but Python has a built-in module called random that can be used to make random numbers:

```bash
import random
```
Example:- 1 
- Import the random module, and display a random number between 1 and 9:
```bash
import random
print(random.randrange(1, 10))
```

Example:- 2
```bash
import random

# randomly getting a number b/w 1 to 6 like a dic
x=random.randint(1,6)
print(x)
# generate random floating number
y=random.random()
print(y)

#creatin a rock paper scissors list
list1=["rock"," paper" ,"scissors"]
z=random.choice(list1)
print(z)
# shuffling of cards
cards=[1,2,3,4,5,6,7,8,9,"j","Q","K"]
random.shuffle(cards)
print(cards)
```
output:-
```bash
5
0.9604905666140859
 paper
[4, 2, 9, 7, 3, 8, 'K', 6, 5, 'j', 1, 'Q']
```

