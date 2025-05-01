# Simple-calculation.by

import numpy as np

# Input values
a = int(input("Enter the value: "))
b = int(input("Enter the value: "))

# --addition--
def add():
    return a + b

# --subtraction--
def sub():
    return a - b

# --multiplication--
def X():
    return a * b

# --division--
def div():
    if b == 0:
        return "Zero can't be divisor"
    else:
        return a / b

# Output all operations
print("The value of arithmetic operation is:")
print("Addition:", add())
print("Subtraction:", sub())
print("Multiplication:", X())
print("Division:", div())


