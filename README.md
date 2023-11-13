# Find the GCD of two numbers
## DATE:29.08.2023
## AIM:
To write a program to find the GCD of two numbers using function.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.
## Program:
```
##Program to find the gcd of two number using function.
##Developed by: PAVANA G
##RegisterNumber: 212222230105

def gcd():
    a=int(input())
    b=int(input())
    if(a>b):
        min=b
    else:
        min=a
    for i in range(1,min+1):
        if(a%i==0 and b%i==0):
            g=i
    print("GCD of two numbers is:",g)
```
## Output:
![image](https://github.com/gpavana/GCD-of-two-numbers/assets/118787343/97fef2b8-44da-4ec4-a02e-58cda5ca6d43)
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
