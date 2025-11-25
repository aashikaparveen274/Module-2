# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
def area(radius):
    area = 3.14*radius*radius
    return area

radius = int(input()) 
```
### OUTPUT
![Screenshot 2025-04-27 140700](https://github.com/user-attachments/assets/a4908005-27e2-434a-8af5-0b0dbdbe84d9)

### RESULT
Thus a python program to define a function that accepts radius and returns the area of a circle has been implemented successfully.
