---
title: How to create an array row by column in python?
tags: [External Post, Git]
style: fill
color: light
description: To create an array in Python in the format (row*column), we will use a list, and allocate to each position of this list another list, we will make a list of lists.
---

# Create an array row by column in python

To create an array in Python in the format (row*col), we will use a list, and allocate to each position of this list another list, we will make a list of lists.

We'll start with an empty list called A, and for each position in the list A, we'll allocate another row list of size col, so we'll have our list composed of other lists. After this small procedure, we will be able to use the matrix in the way we are used to, by row and column, for example A[0][1].

The random.randint(1,10) function is just initializing each array position with a random interior between 1 and 10.

Bellow we have an example:

```python
import random
 
def criaMatriz(row,col):
    A = []
    for i in range(row):
        rwo = []
        for j in range(col):
            row = row + [random.randint(1,10)]
        A = A +[row]
    return A
 
if __name__ == "__main__":
    matriz = criaMatriz(2, 3)
```
