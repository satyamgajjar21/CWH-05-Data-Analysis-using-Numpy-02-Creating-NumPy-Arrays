# Creating NumPy Arrays

## Overview
This project demonstrates how to create different types of NumPy arrays and how to inspect their properties. It shows one dimensional arrays two dimensional arrays and explains array attributes such as shape and data type.

## Creating a One Dimensional Array
The notebook creates a simple one dimensional array using NumPy.

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])
print(arr)

## Creating a Two Dimensional Array

## A matrix like structure is created using nested lists which NumPy converts into a two dimensional array.

import numpy as np

arr = np.array([[1, 2, 3], [4, 5, 6]])
print(arr)

## Checking Array Shape

## The shape attribute shows the arrangement of rows and columns.

print(arr.shape)

## Checking Array Data Type

## NumPy arrays store elements of a single type. The dtype attribute shows the internal type.

print(arr.dtype)

## Summary

1 NumPy arrays allow creation of structured numerical data
2 One dimensional arrays represent simple value lists
3 Two dimensional arrays represent matrices
4 Array attributes such as shape and dtype provide insight into structure and memory representation
