# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
using def function
### Step 2:
Takes user input and evaluates it as a Python expression, assigning it to variable l
### Step 3: 
Takes user input and converts it to an integer, assigning it to variable n.
### Step 4:
Using the slicing concept rotate the list
### Step 5: 
Prints a message "After circulating the values are:" followed by the updated list l. 
### Step 6: 
And run the program we get the output


## Program:
```def circulate(): 
     l= eval(input())
     n= int(input())
     l= l[n:]+l[:n]
     print("After circulating the values are:",l)
```

## Output:
![image png (2)](https://github.com/Santhosh-0031/Circulate-the-values-of-N-variables/assets/145551108/25791240-0152-45f0-80bb-b3007dcd1e9f)


## Result:
Thus the circulates the n variable are successfully executed.
