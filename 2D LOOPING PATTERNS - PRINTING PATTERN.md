# Exp.No:2d
## LOOPING PATTERNS - PRINTING SQUARE PATTERN OF NUMBERS
---
### AIM  
To write a Python program to print a square pattern of numbers using loops.

---
### ALGORITHM
1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows and columns.  
3. Loop through rows from `1` to `n`:  
   - For each row, loop through columns from `1` to `n`.  
   - In each column, print the maximum of the current row and column values.  
   - Print a newline after each row.  
4. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
n = int(input())
for i in range(1, n + 1):
    for j in range(1, n + 1):
        print(max(i, j), end=" ")
    print()
```

### OUTPUT
<img width="560" height="567" alt="image" src="https://github.com/user-attachments/assets/a176eadc-5fb8-4268-bc4d-23ca5878f7b7" />


### RESULT
Thus, the Python program to print a square pattern of numbers using loops has been successfully executed and the output is verified.
