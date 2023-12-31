# Dice-roll : Overview
This python program imitates a dice roll by randomly generating a number from one to six using the ['random'](https://docs.google.com/document/d/e/2PACX-1vRefmS0uA4-_PbCjOnj-Vz0wqWi8f3L_lD4dbGF-lWPYCGwXKckUcuHJh0VYXOSHIFbnFhZVdysU3bv/pub) method.
# Main requirements :
* Python 3.12.0
  (It is available in versions as early as 2.1)
# Step-wise implementation :
## Step 1 :
Importing the 'random' module to use the 'randint' method and randomly generate a number from one to six.
```
import random
```
## Step 2 :
Initiating a character to a variable to use as a condition to roll the dice as many times as the user likes. 
```
x = "r"
```
If the user enters anything else other than 'r', the flow of control leaves the loop.
## Step 3 :
The condition is created.
```
while x=="r":
```
As long as the user inputs 'r', the while loop keeps repeating itself. If the user inputs a different input, it exits the loop.
## Step 4 :
The variable 'no' is initialized to a random number from one to six using the 'randint' method to imitate a dice roll.
```
no = random.randint(1,6)
```
## Step 5 :
A condition is set for each value from one to six which displays the dice roll for the respective number mentioned in the condition.
```
    if no == 1:
        print("[-----]")
        print("[     ]")
        print("[  0  ]")
        print("[     ]")
        print("[-----]")
    if no == 2:
        print("[-----]")
        print("[ 0   ]")
        print("[     ]")
        print("[   0 ]")
        print("[-----]")
    if no == 3:
        print("[-----]")
        print("[     ]")
        print("[0 0 0]")
        print("[     ]")
        print("[-----]")
    if no == 4:
        print("[-----]")
        print("[0   0]")
        print("[     ]")
        print("[0   0]")
        print("[-----]")
    if no == 5:
        print("[-----]")
        print("[0   0]")
        print("[  0  ]")
        print("[0   0]")
        print("[-----]")
    if no == 6:
        print("[-----]")
        print("[0 0 0]")
        print("[     ]")
        print("[0 0 0]")
        print("[-----]")
```
## Step 6 :
The variable 'x' is initiated by the user. If the user inputs 'r', the loop repeats. If the user inputs 'x', the flow of control exits the loop.
```
x=input("press r to roll again and x to exit:")
```
# Entire program:
```
import random
x = "y"
while x == "y":
	no = random.randint(1,6)
	if no == 1:
		print("[-----]")
		print("[     ]")
		print("[  0  ]")
		print("[     ]")
		print("[-----]")
	if no == 2:
		print("[-----]")
		print("[ 0   ]")
		print("[     ]")
		print("[   0 ]")
		print("[-----]")
	if no == 3:
		print("[-----]")
		print("[     ]")
		print("[0 0 0]")
		print("[     ]")
		print("[-----]")
	if no == 4:
		print("[-----]")
		print("[0   0]")
		print("[     ]")
		print("[0   0]")
		print("[-----]")
	if no == 5:
		print("[-----]")
		print("[0   0]")
		print("[  0  ]")
		print("[0   0]")
		print("[-----]")
	if no == 6:
		print("[-----]")
		print("[0 0 0]")
		print("[     ]")
		print("[0 0 0]")
		print("[-----]")
		
	x=input("press y to roll again and n to exit:")
	print("\n")
```
## Output :
![py](https://github.com/Rachel-Eva/Dice-roll/assets/145921131/9568919c-eea7-42fb-a846-34f6f3d3f58f)
