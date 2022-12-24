# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
use def function to circulate 
### Step 2: 
get the input l in eval and n in int
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the output
### Step 6: 
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
!["output"](/circulate%20output.png)

## Result:
Thus the python program for circulate the values for n variables is excecuted sucessfully