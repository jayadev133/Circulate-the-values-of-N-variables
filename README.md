# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: def circulate(variables):
### Step 2: n = int(input("Enter the number of variables: "))
### Step 3: variables_list = [int(input(f"Enter value for variable {i + 1}: ")) for i in range(n)]
Get the value from the user for the number of rotation
### Step 4: rotations = int(input("Enter the number of rotations: "))
Using the slicing concept rotate the list

### Step 5: for _ in range(rotations):
### Step 6: print("Updated values after circulation:", variables_list)
## Program:
```
#Program to circulate N values.
#Developed by: 
#RegisterNumber:
def circulate():
    l=eval(input())
    n=eval(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2023-11-26 132501](https://github.com/jayadev133/Circulate-the-values-of-N-variables/assets/150319465/5d0ed4f8-405f-41dd-80b3-056fee81bb6c)


## Result:Thus a python program to circulate the n variables using function concept is succesfully exicuted 
