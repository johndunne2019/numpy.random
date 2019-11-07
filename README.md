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

## There are 4 main sections in this assignment
1. Explain the overall use of the numpy.random package.
2. Explain the use of the "Simple random data" and Permutations" functions.
3. Explain the use and purpose of at least five "Distributions" functions.
4. Explain the use of seeds in generating pseudorandom numbers. 

## About jupyter notebook

**Below are some interesting facts I learnt about jupyter notebook through lecture videos and further research**

* jupyter notebooks contain cells and the user can enter as many arguments as they like in each cell however jupyter will only return the result of the last entered argument in the cell by default. In order to have the results of all arguments in a cell returned the user must wrap each argument in a print statement.
* jupyter acts like ipython with the key difference that the user interacts with the jupyter browser which offers an extra layer of functionality including the user can use the mouse to move around and select different areas of the notebook. 
* There are 2 different modes when viewing a cell in jupyter, edit mode which appears in green on the left side of the cell and read mode which appears in blue on the left side of the cell.
* There are 2 different modes that can be used when writing in a jupyter notebook - markdown and code. To move between the 2 modes when writing in a notebook the user can hit the ESC key and then M to move to markdown mode and Y to move to code mode. 
* When a user wants to execute an argument they should hold down the shift key and press enter and the output will be displayed in the notebook. 
* There are keyboard shortcuts that can be used, one example is a which adds "a" new cells above the cell the cursor is currently located in and "b" which adds a new cell below the cell the cursor is currently located in. A full list of keyboard shortcuts can be accessed in the help section of the jupyter browser. 
* The numbers that appears on the left side of the screen on the cells containing code indicate the order in which the commands were passed to the kernel. jupyter remembers the arguments that have been previously passed to the kernel. 
* The user can reset the kernel and clear output by going to the toolbar in the browser and selecting restart and clear output. When the user sends each argument to the kernel after this point they will see the numbers on the left hand side start again from 1. 

## References 
**This section contains details on the references and research that went into compiling this project. The references are also listed in each section of the jupyter notebook.**

**jupyter notebook**

* Embed images in jupyter notebook- https://stackoverflow.com/questions/32370281/how-to-embed-image-or-picture-in-jupyter-notebook-either-from-a-local-machine-o
* Mastering Markdown - https://guides.github.com/features/mastering-markdown/
* Markdown cells - https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html
* Markdown - https://www.tutorialspoint.com/jupyter/jupyter_notebook_markdown_cells.htm

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
* Blog post on matplotlib:  https://www.machinelearningplus.com/plots/matplotlib-tutorial-complete-guide-python-plot-examples/#3.-How-to-draw-two-sets-of-scatterplots-in-same-plot
* Python plotting with matplotlib: https://realpython.com/python-matplotlib-guide/
* matplotlib.pyplot.subplot documentation: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.subplot.html

**Section 0 - Introduction to NumPy**
* Official numpy documentation: https://numpy.org/
* Official NumPy tutorial: https://numpy.org/devdocs/user/quickstart.html
* What is NumPy: https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html
* Learn NumPy in 5 minutes tutorial: https://www.youtube.com/watch?v=xECXZ3tyONo
* Complete Python NumPy tutorial: https://www.youtube.com/watch?v=GB9ByFAIAH4
* NumPy Python image: https://i2.wp.com/www.simplifiedpython.net/wp-content/uploads/2018/11/Python-NumPy-14.png?resize=595%2C233&ssl=1

**Section 1 - What is numpy.random and what is the overall purpose of the package**
* numpy.random documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html
* Youtube tutorial: https://www.youtube.com/watch?v=uhP7_Of5WX8&t=14s
* Numpy Random ALL EXPLAINED!!!: https://www.youtube.com/watch?v=uhP7_Of5WX8&t=14s

**Section 2.1 - Simple Random Data**
* Simple Random Data full list of functions:  https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html#simple-random-data

**Section 2.1.1- numpy.random.rand**
* numpy.random.rand documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.rand.html#numpy.random.rand
* Uniform distribution: http://mathworld.wolfram.com/UniformDistribution.html
* Plotting 2 scatter plots side by side:  https://www.machinelearningplus.com/plots/matplotlib-tutorial-complete-guide-python-plot-examples/#3.-How-to-draw-two-sets-of-scatterplots-in-same-plot
* matplotlib.pyplot.subplot documentation: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.subplot.html
* matplotlib.axes.Axes.set_title: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.set_title.html#matplotlib.axes.Axes.set_title

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
* Shuffle multidimensional array: https://stackoverflow.com/questions/35646908/numpy-shuffle-multidimensional-array-by-row-only-keep-column-order-unchanged

**Section 2.2.2 - numpy.random.permutation**
* numpy.random.permutation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.permutation.html#numpy.random.permutation
* There is a good explanation of the difference between numpy.random.shuffle and numpy.random.permutation here: https://stackoverflow.com/questions/15474159/shuffle-vs-permute-numpy
* numpy.random.permutation: https://docs.w3cub.com/numpy~1.14/generated/numpy.random.permutation/

**Section 3 - Distributions**
* This is the link to the documentation on Distributions within the numpy.random function: https://docs.scipy.org/doc/numpy-1.16.0/reference/routines.random.html

**Section 3.0 - What is a probability Distribution?**
* Expected value and variance: https://machinelearningmastery.com/what-are-probability-distributions/
* Probability distribution: https://stattrek.com/probability-distributions/probability-distribution.aspx
* Probability: https://towardsdatascience.com/basic-probability-theory-and-statistics-3105ab637213
* Random variables: https://towardsdatascience.com/basic-probability-theory-and-statistics-3105ab637213
* Random variables and probability distributions: https://www.britannica.com/science/statistics/Random-variables-and-probability-distributions

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

**Section 3.3 - standard_normal([size])**
* numpy.random.standard_normal documentation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.standard_normal.html#numpy.random.standard_normal
* Image of standard_normal distribution:  https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* Definition of standard_normal distribution: https://mathbitsnotebook.com/Algebra2/Statistics/STstandardNormalDistribution.html
* The standard normal distribution: http://sphweb.bumc.bu.edu/otlt/MPH-Modules/BS/BS704_Probability/BS704_Probability9.html

**Section 3.4 - Binomial Distribution**
* The numpy.random.binomial documemtation: https://docs.scipy.org/doc/numpy-1.16.0/reference/generated/numpy.random.binomial.html#numpy.random.binomial
* Binomial distribution: https://www.britannica.com/science/binomial-distribution
* Binomisl distribution: https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/binomial-theorem/binomial-distribution-formula/
* Video on Binomial distribution: https://www.khanacademy.org/math/statistics-probability/random-variables-stats-library/binomial-random-variables/v/binomial-distribution
* How to tell if an experiment is binomial: https://www.youtube.com/watch?v=NhqkZuWwGrA
* Image of Binomial distribution: Image from: http://www.malinc.se/math/iframeImages/s_binomial1.png
* The Binomial Distribution Formula: https://www.youtube.com/watch?v=BA0OI41VzBA
* Example of binomial distribution in call center analyses: https://towardsdatascience.com/fun-with-the-binomial-distribution-96a5ecabf65b
* How to graph the binomial distribution: https://www.dummies.com/education/math/business-statistics/how-to-graph-the-binomial-distribution/

**Section 3.5 - poisson([lam, size]) - References**
* numpy.random.poisson documentation: https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.poisson.html#numpy.random.poisson
* Random variables and probability distributions: https://www.britannica.com/science/statistics/Random-variables-and-probability-distributions
* The Poisson Distribution: https://www.youtube.com/watch?v=Fk02TW6reiA
* The Poisson Distribution and Poisson Process Explained: https://towardsdatascience.com/the-poisson-distribution-and-poisson-process-explained-4e2cb17d459
* Poisson distribution: https://www.datacamp.com/community/tutorials/probability-distributions-python

**Section 4 - The use of seeds in generating pseudorandom numbers - References**
* numpy.random.seed documentation: https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.seed.html#numpy.random.seed
* Pseudo Random Number Generator (PRNG)- https://www.geeksforgeeks.org/pseudo-random-number-generator-prng/
* Introduction to Randomness and Random Numbers: https://www.random.org/randomness/
* What does numpy.random.seed do: https://stackoverflow.com/questions/21494489/what-does-numpy-random-seed0-do
* Khan Academy: https://www.khanacademy.org/computing/computer-science/cryptography/crypt/v/random-vs-pseudorandom-number-generators
* numpy random seed blog post: https://www.sharpsightlabs.com/blog/numpy-random-seed/
* How Does Your Computer Generate Random Numbers? - https://www.sicara.ai/blog/2019-01-28-how-computer-generate-random-numbers