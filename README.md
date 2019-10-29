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

**Section 2.1 - Simple Random Data**


**Section 2.2 - Permutations**


### Section 3 - "Distributions"

### Section 4  - The use of Seeds in generating pseudorandom numbers

## References 
**This section contains details on the references and research that went into compiling this project.**
* How to write to Readme file in markdown: https://guides.github.com/features/mastering-markdown/ 

**Section 0 - Introduction to NumPy**
* Official numpy documentation: https://numpy.org/
* Official NumPy tutorial: https://numpy.org/devdocs/user/quickstart.html
* What is NumPy: https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html
* Learn NumPy in 5 minutes tutorial: https://www.youtube.com/watch?v=xECXZ3tyONo
* Complete Python NumPy tutorial: https://www.youtube.com/watch?v=GB9ByFAIAH4

**matplotlib**
* matplotlib.pyplot documentation: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html
* Blog post tutorial on matplotlib: https://www.machinelearningplus.com/plots/matplotlib-tutorial-complete-guide-python-plot-examples/
* matplotblib.pylplot.show(): https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.show.html#matplotlib.pyplot.show
* matplotlib.pyplot.plot(): https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.plot.html#matplotlib.pyplot.plot
* matplotlib.pyplot.title(): https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.title.html#matplotlib.pyplot.title
* matplotlib.pyplot.xlabel: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.xlabel.html#matplotlib.pyplot.xlabel
* matplotlib.pyplot.ylabel: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.ylabel.html#matplotlib.pyplot.ylabel
* matplotlib.pyplot.hist(): https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.hist.html#matplotlib.pyplot.hist
* Resizing pyplot plots and figures in jupyter notebook using pylot.rcparams: https://stackoverflow.com/questions/36367986/how-to-make-inline-plots-in-jupyter-notebook-larger
* pyplot.rcparams documentation: https://matplotlib.org/3.1.1/tutorials/introductory/customizing.html and https://matplotlib.org/3.1.1/api/matplotlib_configuration_api.html#matplotlib.rcParams
* Changing line size and line width read in the text section of the matplotlib.pyplot documentation: https://matplotlib.org/tutorials/introductory/pyplot.html
* Changing the appearance of a line in a plot in pyplot: https://www.machinelearningplus.com/plots/matplotlib-tutorial-complete-guide-python-plot-examples/

**Section 1 - What is numpy.random and what is the overall purpose of the package**
* numpy.random documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html


**Section 2.1 - Simple Random Data**
* Simple Random Data full list of functions:  https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html#simple-random-data

**Section 2.1.1- numpy.random.rand**
* numpy.random.rand documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.rand.html#numpy.random.rand
* Uniform distribution: http://mathworld.wolfram.com/UniformDistribution.html

**Section 2.1.2- numpy.random.randn**
* numpy.random.randn: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.randn.html#numpy.random.randn
* numpy.random.randn: https://onlinecoursetutorials.com/numpy/numpy-random-randn-function-with-example-in-python/
* Normal distribution: https://www.tutorialspoint.com/python_data_science/python_normal_distribution.htm
* Normal distribution: https://www.mathsisfun.com/data/standard-normal-distribution.html

**Section 2.1.3 - numpy.random.bytes**
* numpy.random.bytes: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.bytes.html#numpy.random.bytes

**Section 2.1.4 - numpy.random.random_sample**

**Section 2.2 - Permutations**
* numpy.random Permutations documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html

**Section 2.2.1 - numpy.random.shuffle**
* numpy.random.shuffle documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.shuffle.html#numpy.random.shuffle
* How to randomly shuffle an array in python using numpy- https://www.science-emergence.com/Articles/How-to-randomly-shuffle-an-array-in-python-using-numpy/

**Section 2.2.2 - numpy.random.permutation**
* numpy.random.permutation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.permutation.html#numpy.random.permutation
* There is a good explanation of the difference between numpy.random.shuffle and numpy.random.permutation here: https://stackoverflow.com/questions/15474159/shuffle-vs-permute-numpy
* numpy.random.permutation: https://docs.w3cub.com/numpy~1.14/generated/numpy.random.permutation/

**Section 3 - Distributions**
* This is the link to the documentation on Distributions within the numpy.random function: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html

**Section 3.1 - normal([loc, scale, size])**
* numpy.random.normal documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.normal.html#numpy.random.normal
* Normal distribution- https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/normal-distributions/
* Standard normal distribution: https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* The Empirical rule Youtube video: https://www.youtube.com/watch?time_continue=6&v=hQTvdD8vtio
* What is the Empirical rule: https://www.statisticshowto.datasciencecentral.com/empirical-rule-2/ and https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* Image of the Empirical rule: https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/normal-distributions/
* Image of the normal bell curve distribution: https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FBell-curve-and-standard-deviation_fig3_47554522&psig=AOvVaw1gtLSAMO5j4HibQ1LDTwaI&ust=1572441726238000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJCW0pnIweUCFQAAAAAdAAAAABAD
* numpy.mean: https://docs.scipy.org/doc/numpy/reference/generated/numpy.mean.html
* numpy.std: https://docs.scipy.org/doc/numpy/reference/generated/numpy.std.html
* numpy.amin: https://docs.scipy.org/doc/numpy/reference/generated/numpy.amin.html#numpy.amin
* numpy.amax: https://docs.scipy.org/doc/numpy/reference/generated/numpy.amax.html#numpy.amax
* numpy.median: https://docs.scipy.org/doc/numpy/reference/generated/numpy.median.html
* numpy.percentile: https://docs.scipy.org/doc/numpy/reference/generated/numpy.percentile.html#numpy.percentile

**Section 3.2 - uniform([low, high, size])**
* numpy.random.uniform documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.uniform.html#numpy.random.uniform
* Uniform distribution: https://www.investopedia.com/terms/u/uniform-distribution.asp
* Image of uniform distribution: https://docs.scipy.org/doc/numpy-1.15.0/reference/generated/numpy.random.uniform.html


**Section 3.1 - standard_normal([size])**
* numpy.random.standard_normal documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.standard_normal.html#numpy.random.standard_normal
* Image of standard_normal distribution:  https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* Definition of standard_normal distribution: https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* The standard normal distribution: http://sphweb.bumc.bu.edu/otlt/MPH-Modules/BS/BS704_Probability/BS704_Probability9.html