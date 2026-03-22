# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - EXPRESSION EVALUATION
---
### AIM  
To write a Python program to calculate the value of the expression `(x + 10) + (y + 2) * z` using a lambda function.

---
### ALGORITHM
1. Begin the program.  
2. Read three integers `x`, `y`, and `z` from the user using `input()`.  
3. Define a lambda function that takes three arguments `x`, `y`, and `z`.  
4. The lambda function computes the expression `(x + 10) + (y + 2) * z`.  
5. Call the lambda function by passing `x`, `y`, and `z` as arguments.  
6. Print the result.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
x = int(input())
y = int(input())
z = int(input())
expression = lambda x, y, z: (x + 10) + (y + 2) * z
print(expression(x, y, z))
```

### OUTPUT
<img width="365" height="276" alt="image" src="https://github.com/user-attachments/assets/e1fca62f-e6db-4feb-b4c5-b284d65b9b53" />


### RESULT
Thus, the Python program to calculate the value of the expression `(x + 10) + (y + 2) * z` using a lambda function has been successfully executed and the output is verified.
