Definition :- 

A NumPy array, also called an **ndarray**, is a fundamental data structure in the NumPy library for Python. It's a powerful N-dimensional array that efficiently stores and manipulates numerical data. Here are some key points about NumPy arrays:

Efficiency: Compared to traditional Python lists, NumPy arrays are designed for numerical data and offer superior performance in terms of speed and memory usage. This is because all the elements in a NumPy array must be of the same data type, allowing for optimized operations.

Dimensions: NumPy arrays can be one-dimensional (1D), two-dimensional (2D), or even higher-dimensional (3D, 4D, etc.).  1D arrays are essentially rows of numbers, 2D arrays are grids of numbers like matrices, and higher dimensional arrays can represent more complex data structures.

Data Types: All the elements within a NumPy array must have the same data type. This could be **integers, floats, strings, or booleans**.  Specifying the data type upfront allows for optimized storage and operations.

Creation: There are several ways to create NumPy arrays. You can convert a Python list of numbers to a NumPy array, use built-in functions to generate arrays of zeros or ones, or specify a range of numbers.

# 1D numpy array for a list
import numpy as np
arr=np.array([1,2,3])
arr
Out[1]:
array([1, 2, 3])
In [2]:

# 3*3 array from a list
import numpy as np
arr=([1,2,3],[4,5,6],[7,8,9])
changedarr=np.array(arr)
changedarr
Out[2]:
array([[1, 2, 3],
       [4, 5, 6],
       [7, 8, 9]])
In [3]:

# Creating a numpy array
arr=np.arange(1,10,2) #start,Stop,Step Size
arr
Out[3]:
array([1, 3, 5, 7, 9])
In [4]:

# Zeros
np.zeros(5)
Out[4]:
array([0., 0., 0., 0., 0.])
In [6]:

np.zeros(2)
Out[6]:
array([0., 0.])
In [7]:
# Ones
np.ones(5)
Out[7]:
array([1., 1., 1., 1., 1.])
