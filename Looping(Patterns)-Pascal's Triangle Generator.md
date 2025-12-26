# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
import math
n=int(input())
for i in range(n):
    for s in range(n-i-1):
        print(" ",end="")
    for j in range(i+1):
        print(f"{math.comb(i,j)} ",end="")            
    print()
```

## Sample Output
<img width="617" height="692" alt="530163097-ebd2c98e-4b8e-4dcf-bfa7-4327286ac694" src="https://github.com/user-attachments/assets/9377e9e9-ff57-4c86-911f-d866e1e6f42c" />

## Result

We output successful output
