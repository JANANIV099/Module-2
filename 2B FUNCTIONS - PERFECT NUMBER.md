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
#Reg.No:212223060099
#Name:JANANI V
#Add your Code Here

def printValues(N):
    result = [i**2 for i in range(1, N)]
    print(result)



```
### OUTPUT

<img width="1422" height="160" alt="image" src="https://github.com/user-attachments/assets/2200448c-0b71-49de-864e-84ae638f363c" />

### RESULT
Thus, the python code is written and executed successfully.
