# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the n variables from the user 
### Step 2:
Get the input 
### Step 3:
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
Print the value it would be interchanged
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Farhana H
#RegisterNumber:23012987

def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```


## Output:
![image](https://github.com/syedfayaz3105/Circulate-the-values-of-N-variables/assets/147144126/1ebb4d6a-960f-41b0-901f-6ea698568064)


## Result:
thus the circulation of n variables successfully executed.
