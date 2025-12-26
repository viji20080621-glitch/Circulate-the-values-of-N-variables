# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
# Program to circulate the values of N variables
# Developed By: Vijiyalakshmi A
# Register Number: 212225240185
```
def circulate():
    values = eval(input())
    k = int(input())
    
    k = k % len(values)
    result = values[k:] + values[:k]
    
    print("After circulating the values are:", result)

```
## Output:

<img width="1275" height="513" alt="Screenshot 2025-12-26 202649" src="https://github.com/user-attachments/assets/42263ef2-dad1-4443-a946-d97f3637da78" />

## Result:
