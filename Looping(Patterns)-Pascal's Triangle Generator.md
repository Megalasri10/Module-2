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
Add Code Here
```
import math
rows = 2
for i in range(rows):
    print(" " * (rows - i - 1), end="")
    for j in range(i + 1):
        value = math.comb(i, j)  
        print(value, end=" ")
    print()  
```


## Sample Output
<img width="1685" height="487" alt="image" src="https://github.com/user-attachments/assets/d57b206c-d49e-4387-8a3d-2642b967026d" />

## Result
The code is executed successfully.
