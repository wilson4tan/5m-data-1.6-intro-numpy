# Assignment

## Brief

Write the Python codes for the following questions.

## Instructions

Paste the answer as Python in the answer code section below each question.

### Question 1

Given the following numpy array:

```python
arr = np.array([1, 2, 3, 4, 5])
```

Write a Python code to multiply each element in the array by 2.

Answer:

```python
import numpy as np
arr = np.array([1, 2, 3, 4, 5])
arr = arr*2
print(arr)
```

### Question 2

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to select the second row of the array.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(arr[1]) 
```

### Question 3

Create a 2D numpy array of shape (5, 5) filled with the number 1.

Answer:

```python
np.ones((5,5))
```

### Question 4

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the sum of all the elements in each row.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
new_arr = arr + arr
print(new_arr)
```

### Question 5

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the average of all the elements.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
new_mean_arr = np.average(arr)
print(new_mean_arr)
```

## Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
