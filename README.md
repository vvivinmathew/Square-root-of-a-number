# DATE:
# EX-5 Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
#Developed by: Bhuvaneshwari M 
#RegisterNumber: 212223230033
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))   

```

## Output:
![Screenshot 2024-09-04 194632](https://github.com/user-attachments/assets/fe65dd91-815d-4326-86f5-0b75542af0af)

![Screenshot 2024-09-04 194713](https://github.com/user-attachments/assets/9ed8c5e4-d4e7-4215-bf1b-121f13ccaa26)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
