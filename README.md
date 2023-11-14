# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the both values
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Tamilarasan K S.
#RegisterNumber:23000080

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![values](https://github.com/KSTamilarasan17/Circulate-the-values-of-N-variables/assets/138849236/5d2d9c42-2bb7-4391-b402-c4853ecdf8cb)


## Result:
Thus the circulate the values of N variables is successfully executed
