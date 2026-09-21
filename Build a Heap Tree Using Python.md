# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```python
import heapq
def heaptree(H):
    heapq.heapify(H)
    print("The created Heap is",H)
```

## OUTPUT

<img width="1176" height="166" alt="image" src="https://github.com/user-attachments/assets/b60328b5-4548-4e39-b21f-eff2f99a94e1" />


## RESULT
Thus the python program for to build a heap tree using appropriate Python package and function has been implemented and executed successfully.
