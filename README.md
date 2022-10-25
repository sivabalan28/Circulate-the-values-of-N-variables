# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
define circulate
### Step 2:
get input from the user 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
print the output 
## Program:
```python 
#Program to circulate n variables using function
#Developed by: Sivabalan S
#Register number: 22004401
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are:",a)
```
## Output:
![output](/noutput.png)

## Result:
program has been created for circulating the n variables using function concept
