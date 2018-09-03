# Convolution as Matrix Multiplication
Step by step explanation of 2D convolution implemented as matrix multiplication using toeplitz matrices


## What is the purpose?

Instead of using `for-loops` to perform 2D convolution on images (or any other 2D matrices) we can convert the filter to a `Toeplitz matrix` and image to a vector and do the convolution just by one `matrix multiplication` (and of course some post-processing on the result of this multiplication to get the final result)

## Why do we do that?
There are many efficient matrix multiplication algorithms, so using them we can have an efficient implementation of convolution operation.

## What is in this document?
Mathematical and algorithmic explanation of this process. I will put a naive Python implementation of this algorithm to make it more clear.<br>

Implemented in python (jupyter notebook) <br>
[Look at the notebook](https://github.com/alisaaalehi/convolution_as_multiplication/blob/master/Convolution_as_multiplication.ipynb)
 or [Look at this pdf in the repository for details](https://github.com/alisaaalehi/convolution_as_multiplication/blob/master/ConvAsMulExplained.pdf)
