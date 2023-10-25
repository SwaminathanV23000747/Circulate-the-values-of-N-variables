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
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```python
#Program to circulate N values.
#Developed by: SWAMINATHAN V
#RegisterNumber:23000747
def circulate():
    lst=eval(input())
    n=int(input())
    result=lst[n:]+lst[:n]
    print("After circulating the values are:",result)
```
## Output:
![output](circulate%20n%20variable.png)
## Result:
Thus the swapping of two values are successfully executed.

