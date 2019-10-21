# numpy.random
My assignment on numpy.random as part of the Programming for Data Analysis 2019 module

This repository contains my assignment for the module Fundamentals of Data Analysis at GMIT. See here for the instructions: https://github.com/brianmcginley/ProgDA/raw/master/ProgDA_Assignment.pdf. References and resources I used in compiling this project are listed in the references section at the foot of this Readme file.

## Author
John Dunne

## How to download this repository
1. Go to GitHub.
2. Go to my repository: https://github.com/johndunne2019/numpy.random
3. Click the clone/download button.
4. Save the repository to a local folder location on your machine.
5. You will need to navigate to this folder location on the command line in order to run the program.
6. Details on how to run each individual script in this repository is included later in this Readme file.

## How to run the jupyter notebook
1. On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.
2. Type jupyter notebook on the command line and press enter
3. After a short wait jupyter notebook will open in your web browser. 
4. Open the numpy.random.ipynb notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
5. if you want to run the code in any cell hold down the shift key and press enter and the command will run and the output wil be displayed in the next cell. 
6. To change between edit and read mode at any time press the ESC key.
7. When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.

## About this Assignment
This assignment concerns the numpy.random package in Python. In completing this assignment I will try to explain in detail the use of the numpy.random package in Python using explanations and examples. I will create a jupyter notebook and use this to show examples of numpy.random and its uses.

## What is NumPy?
The official NumPy documentation is here: https://numpy.org/ and the tutorial is here: https://numpy.org/devdocs/user/quickstart.html. NumPy is used to work with arrays and provides many different functions that can be used to work with arrays. One important point to note that was discussed in one of the lecture videos is that NumPy likes all the data it is working with to be the same type, for example all floating point or all integers. Another useful package that can be used to work with data sets that have combinations of different data types is pandas.  

I have taken the below section from the official NumPy documentation to help explain the package further:

*NumPy is the fundamental package for scientific computing with Python. It contains among other things:*

* *a powerful N-dimensional array object*
* *sophisticated (broadcasting) functions*
* *tools for integrating C/C++ and Fortran code*
* *useful linear algebra, Fourier transform, and random number capabilities*

**Taken from NumPy documentations here: https://numpy.org/**

The main object within NumPy is the multidimensional array. An array is a table of elements that contains data all of the same type, usually numbers. An example array would look like - [1,2,3,4]. The array class in NumPy is known as ndarray or numpy.array and withing this class there are many functions that can be used to manipulate datas within arrays. Some examples are:

* ndarray.ndim - returns the number of axes in an array
* ndarray.shape - returns the dimensions of the array, for example the number of rows and columns
* ndarray.size - the total number of elements in the array

Some examples are shown in the jupyter notebook that I have written.

## There are 4 main sections in this assignment
* Explain the overall use of the numpy.random package.
* Explain the use of the "Simple random data" and Permutations" functions.
* Explain the use and purpose of at least five "Distributions" functions.
* Explain the use of seeds in generating pseudorandom numbers. 

## Further Details on each section of the project in the jupyter notebook

### Section 1 - What is numpy.random and what is the overall purpose of the package?
numpy.random is a package in Python that is used to generate random sampling from a set of parameters entered by the user.
The official numpy.random documentation can be viewed here: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html. There are many different functions within the numpy.random package which can be used for different purposes and a full list of the functions is shown in the documentation at the link above. 

### Section 2 - "Simple Random Data" and "Permutations"

### Section 3 - "Distributions"

### Section 4  - The use of Seeds in generating pseudorandom numbers

## References 
**This section contains details on the references and research that went into compiling this project.**
* How to write to Readme file in markdown: https://guides.github.com/features/mastering-markdown/ 

**NumPy**
* Official numpy documentation: https://numpy.org/
* Official NumPy tutorial: https://numpy.org/devdocs/user/quickstart.html
* What is NumPy: https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html
* Learn NumPy in 5 minutes tutorial: https://www.youtube.com/watch?v=xECXZ3tyONo

**numpy.random**
* numpy.random documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html


**Simple Random Data**
* Simple Random Data full list of functions:  https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html#simple-random-data
* numpy.random.rand documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.rand.html#numpy.random.rand
* Uniform distribution: http://mathworld.wolfram.com/UniformDistribution.html
* numpy.random.randn: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.randn.html#numpy.random.randn
* Normal distribution: https://www.tutorialspoint.com/python_data_science/python_normal_distribution.htm
* numpy.random.bytes: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.bytes.html#numpy.random.bytes
