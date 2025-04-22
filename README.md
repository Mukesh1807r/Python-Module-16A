# Constructing an AVL Tree and Finding Its Length

## 📌 Aim
To write a Python program that constructs an **AVL Tree** from a given list of elements and prints the **length of the AVL Tree** using appropriate Python packages and built-in functions.

---

## 🛠 Procedure
1. Import the `AVL` class from the `TreeAVL` module.
2. Define a function `Construct_AVL(L)` that:
   - Creates an AVL tree from the input list `L`.
   - Uses the built-in attribute `length_tree` to calculate the number of nodes.
3. Call the function with a predefined list to demonstrate the result.

---

## 💻 Program

```python
from TreeAVL.AVL import AVL

def Construct_AVL(L):
    tree = AVL(L)
    print("Length of an AVL Tree is", tree.length_tree)
```
---
## Output

![image](https://github.com/user-attachments/assets/59413218-b0b0-4d61-8bcb-154e216b0253)

---
## Result

Thus, the program was successfully created and executed to construct an AVL tree and determine its length.


