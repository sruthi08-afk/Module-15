# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```python
from binarytree import build
nodes=[10,12,5,3,4,11,2,None,None,6,7,None,None,None,8]
root=build(nodes)
print("Binary tree:")
for i in (root.values):
  print(i,"-->",end="")
print("\nlevel order traversal:",root.levelorder)
print("\nInorder traversal:",root.inorder)
print("\nPreorder traversal:",root.preorder)
print("\nPostorder traversal:",root.postorder)
```

## OUTPUT
<img width="1252" height="215" alt="image" src="https://github.com/user-attachments/assets/389605d2-c990-453a-b4de-e922a277b100" />


## RESULT
Thus the python program for to build the given expression tree and print the inorder and postorder traversals has been implemented and executed successfully.
