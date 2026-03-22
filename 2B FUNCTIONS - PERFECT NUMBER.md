# Exp.No:2b  
## FUNCTIONS - PRIME NUMBER
### AIM  
To write a Python program to check if a number is a Prime number using the concept of functions.

---
### ALGORITHM
1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `primeNumber(n)` with the following steps:  
    - If `n` is less than or equal to 1, print it is not a prime number.  
    - Iterate through all numbers from 2 to `n//2`.  
    - If any number `i` divides `n` perfectly (i.e., `n % i == 0`), print it is not a prime number and return.  
    - If no divisor is found, print it is a prime number.  
5. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
def primeNumber(n):
    if n <= 1:
        print("Given number", n, "is not a Prime Number")
        return
    for i in range(2, n // 2 + 1):
        if n % i == 0:
            print("Given number", n, "is not a Prime Number")
            return
    print("Given number", n, "is a Prime Number")

n = int(input())
primeNumber(n)
```

### OUTPUT
<img width="870" height="204" alt="image" src="https://github.com/user-attachments/assets/da405070-c2fe-4d90-a888-b2e6d485c012" />


### RESULT
Thus, the Python program to check if a number is a Prime number using the concept of functions has been successfully executed and the output is verified.
