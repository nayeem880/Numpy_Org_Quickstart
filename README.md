# Numpy_org_Quickstart
First numpy repository from numpy.org Quickstart tutorial for basic and fundamental numpy practice !
### Prerequisites
Before reading this tutorial you should know a bit of Python. If you would like to refresh your memory, take a look at the Python tutorial.

If you wish to work the examples in this tutorial, you must also have some software installed on your computer. Please see https://scipy.org/install.html for instructions.

### The Basics
NumPy’s main object is the homogeneous multidimensional array. It is a table of elements (usually numbers), all of the same type, indexed by a tuple of non-negative integers. In NumPy dimensions are called axes.

For example, the coordinates of a point in 3D space [1, 2, 1] has one axis. That axis has 3 elements in it, so we say it has a length of 3. In the example pictured below, the array has 2 axes. The first axis has a length of 2, the second axis has a length of 3.
```
[[ 1., 0., 0.],
 [ 0., 1., 2.]] 
 ```
NumPy’s array class is called `ndarray`. It is also known by the alias `array`. Note that `numpy.array` is not the same as the Standard Python Library class `array.array`, which only handles one-dimensional arrays and offers less functionality. The more important attributes of an `ndarray ` object are:

##### ndarray.ndim
the number of axes (dimensions) of the array.
##### ndarray.shape
the dimensions of the array. This is a tuple of integers indicating the size of the array in each dimension. For a matrix with n rows and m columns, shape will be (n,m). The length of the shape tuple is therefore the number of axes, ndim.
##### ndarray.size
the total number of elements of the array. This is equal to the product of the elements of shape.
##### ndarray.dtype
an object describing the type of the elements in the array. One can create or specify dtype’s using standard Python types. Additionally NumPy provides types of its own. numpy.int32, numpy.int16, and numpy.float64 are some examples.
##### ndarray.itemsize
the size in bytes of each element of the array. For example, an array of elements of type float64 has itemsize 8 (=64/8), while one of type complex32 has itemsize 4 (=32/8). It is equivalent to 
` ndarray.dtype.itemsize. `
##### ndarray.data
the buffer containing the actual elements of the array. Normally, we won’t need to use this attribute because we will access the elements in an array using indexing facilities.


<script src="https://gist.github.com/nayeem990/b1d302e56f698c7fb30d6f478a785a9d.js"></script>

#### Numpy Quickstart Gist below :

<script src="https://gist.github.com/nayeem990/b70d39934065009846b0850060844bfb.js"></script>


- [ ] \(Optional) Open a followup issue

  
