# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## Step:
1. Define a function.

## Step:
2. Get the two numbers from the user.

## Step:
3. Compare the two values, to find the smaller number.

## Step:
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:

```
/*
Program to find the gcd of a number using function.
Developed by:A.Ruchitha Reddy 
Reg.no:21005032
*/
```
def gcd():

n1=int(input())

n2=int(input())

if(n1>n2):

smaller=n2

else:

smaller=n1

for i in range(1,smaller+1):

if(n1%i==0 and n2%i==0):

GCD=i

print("GCD of two numbers is:",GCD)

## Output:
![output](https://github.com/RuchithaReddy28/GCD-of-two-numbers/blob/main/IMG-20211218-WA0043.jpg?raw=true)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
