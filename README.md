# Assignment - Programming for Data Analysis

* **Author:** John Paul Lee
* **Github:** JPLee01
* **Email:** G00387906@gmit.ie
* **Created:** 31-10-2020, **Last update:** 22-11-2020
------------------------------------------------------------------------------------------------
**Programming for Data Analysis:** *numpy.random* package in Python

A Jupyter Notebook has been created to explain the *numpy.random* package in Python. This notebook will explain the packages use and detailed explanations of at least five of the distributions provided for in the package, as well as the use of seeds in generating pseudorandom numbers for the Programming of Data Analysis Assignment.

**Lecturer:** Dr. Brian McGinley

The Project instructions can be found at [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment/blob/main/Assignment%20Instructions.pdf)

**Table of Contents**
------------------------------------------------------------------------------------------------

[*numpy.random* package in Python](#Assignment-Programming-for-Data-Analysis)

[1. Introduction](#1-introduction)

[2. Project Repository](#2-project-repository)

[3. numpy.random package](#3-*numpy.random*-package)

[4. Problem Statement](#4-Problem-Statement)

[5. User Guide](#5-User-Guide)

  [5.1 Downloading the Repository](#5.1-Downloading-the-Repository)

  [5.2  Running the Program](#5.2-Running-the-Program)

  [5.3  Libraries](#5.3-Libraries)

[6. Summary, Conclusion and Future Analysis of the numpy.random Package](#6.-Summary,-Conclusion-and-Future-Analysis-of-the-numpy.random-Package)

[7. References](#7-References)

[8. Bibliography](#8-Bibliography)

## 1 Introduction
------------------------------------------------------------------------------------------------

This analysis of *numpy.random* package in Python has been carried out as an assignment of the Programming for Data Analysis module. The aim of this assignment is to help the student gain an understanding of the *numpy.random* package in Python through; detailed explanations of the package, the use of the simple random data and permutations functions, five distributions provided for and the use of seeds in generating pseudorandom numbers. This explanation will be conducted through a Jupyter Notebook which will contain markdown text, images, Python code and Plots. 

## 2 Project Repository
------------------------------------------------------------------------------------------------

The Assignment Repository is the source where all the work associated with
the assignment will be stored. It contains the following files and can be
located [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assignment
  Assignment Instructions.pdf | A PDF copy of the Assignment Instructions
  LICENSE     |    MIT License for the project
  Programming_for_Data_Analysis-Assignment.ipynb | Jupyter Notebook created to explain the *numpy.random* package in Python
  README.md   |    This file; A Description of the Assignment and Instructions

## 3 numpy.random package
------------------------------------------------------------------------------------------------
The *numpy.random* package in Python is a package within the NumPy (Numerical Python) libary for doing random sampling. The package contains some simple random data generation methods, some permutation and distribution functions, and random generator functions. It should also be noted that NumPy is seen as the fundamental package for scientific computing with Python. This is mainly due to its ability to help programmers easily perform numerical computations. A key facet of that viewpoint is the *numpy.random* package and its ability to easliy generate random sampling. 

## 4 Problem Statement
------------------------------------------------------------------------------------------------
As part of the assignment, the student was given a set of instructions which can be viewed [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment/blob/main/Assignment%20Instructions.pdf). As seen, within the instructions a problem statement was printed. It stated that the following assignment concerns the *numpy.random* package in Python. The student is required to create a Jupyter Notebook explaining the use of the package, including detailed explanations of at least five of the distributions provided for in the package.
There are also four distinct tasks to be carried out in the Jupyter notebook:
1. Explain the overall purpose of the package.
2. Explain the use of the “Simple random data” and “Permutations” functions.
3. Explain the use and purpose of at least five “Distributions” functions.
4. Explain the use of seeds in generating pseudorandom numbers.

## 5 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 5.1 Downloading the Repository
The repository is stored at the following: https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green “clone or download” button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 5.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#5.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
Programming_for_Data_Analysis-Assignment.ipynb
```
7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 5.3 Libraries
The following Python libraries were used in the writing of the programs code and are required to successfully run the programs:
* [Numpy](https://www.numpy.org/) - The *numpy.random* library is the subject of the [Programming_for_Data_Analysis-Assignment.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment/blob/main/Programming_for_Data_Analysis-Assignment.ipynb) notebook and its functions are extensively used throughout.
* [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for the manipulation of elements and the creation of certain plots graphs and plots within the [Programming_for_Data_Analysis-Assignment.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment/blob/main/Programming_for_Data_Analysis-Assignment.ipynb) notebook.
* [Seaborn](https://seaborn.pydata.org/) - Used for the creation and manipulation of all plots in the [Programming_for_Data_Analysis-Assignment.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Assignment/blob/main/Programming_for_Data_Analysis-Assignment.ipynb) notebook (Seaborn allows for the extetion of the functionality of Matplotlib).

## 6 Summary, Conclusion and Future Analysis of the numpy.random Package
------------------------------------------------------------------------------------------------
In summary it can be seen that the *numpy.random* package in Python can be used for a variatey of functions in which random data generation is required. The *numpy.random* package is also befenitial to computer scientists as it offers the user the to investigate numerical computations withouthaving to undergo the time consuming process of collecting data. While it is generally said that the numpy.random package uses random numbers, we have seen from analysis that this is not entirely the case and that in fact the numbers can be calculated and premediated. Through analysis it can also be seen that advantages lie in the ability to predetermine random data generation in terms of analysis and hypothesis testing.

In conclusion after completion of the assigmentent the author feels they have gained an indept knowledge of the *numpy.random* package in Python, and also a wider appreciation of the field of random number generation and distribution. As the author did not have substantial experience in random number generation or distribution prior to the commencement of the assignment, extensive research was undertaken. This resulted in the author gaining an experience, understanding and overall insight into random number generation and distribution. The author now feels a level of confidence with regards to data analysis which was not present before undertaking the assignment. The author also feels, that this new knowledge, will be of significant benefit as they continue their studies.

In terms of future analysis of the *numpy.random* package, the scope is endless. In essence, the assignment has only scratched the surface, and hundreds of PhD's could be written to extensively analyse the package. Also in today's data rich world the real life applications of the package are infinite. As Andrew McAfee the is cofounder and codirector of the MIT Initiative on the Digital Economy said *"The world is one big data problem."*

## 7 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

## 8 Bibliography
------------------------------------------------------------------------------------------------
Within the course of this assignment the following sources were used for research purposes:
* Alex Lenail - Understanding and Implementing the Hypergeometric Test in Python, <https://blog.alexlenail.me/understanding-and-implementing-the-hypergeometric-test-in-python-a7db688a7458>

* Better Explained - Easy Permutations and Combinations, <https://betterexplained.com/articles/easy-permutations-and-combinations/>

* Brett Berry - Combinations vs Permutations, <https://medium.com/i-math/combinations-permutations-fa7ac680f0ac#:~:text=The%20difference%20between%20combinations%20and,different%20ordering%20(aka%20permutation)>

* Chris Albon - Generating Random Numbers With NumPy, <https://chrisalbon.com/python/basics/generating_random_numbers_with_numpy/>

* DataCamp - Random Number Generator Using Numpy, <https://www.datacamp.com/community/tutorials/numpy-random>

* David M. Lane - Binomial Distribution, <http://onlinestatbook.com/2/probability/binomial.html>

* Debanjona Bhattacharjya - NumPy.Random.Seed(101) Explained, <https://medium.com/@debanjana.bhattacharyya9818/numpy-random-seed-101-explained-2e96ee3fd90b> 

* Engineering and Statistics HAndbook - 1.3.6.6.19. Poisson Distribution, <https://www.itl.nist.gov/div898/handbook/eda/section3/eda366j.htm>

* EW Weisstein - Poisson Distribution / Poisson Curve: Simple Definition, <https://www.statisticshowto.com/poisson-distribution/>

* Geeks for Geeks - numpy.random.choice() in Python, <https://www.geeksforgeeks.org/numpy-random-choice-in-python/>

* Geek for Geeks - numpy.random.poisson() in Python, <https://www.geeksforgeeks.org/numpy-random-poisson-in-python/>

* Geeks for Geeks - numpy.random.randn() in Python, <https://www.geeksforgeeks.org/numpy-random-randn-python/>

* Geeks for Geeks - Python – Binomial Distribution, <https://www.geeksforgeeks.org/python-binomial-distribution/>

* Geek for Geeks - Python | Numpy np.hypergeometric() method, <https://www.geeksforgeeks.org/python-numpy-np-hypergeometric-method/>

* Jarkko Toivonen - Data Analysis with Python, <https://saskeli.github.io/data-analysis-with-python-summer-2019/numpy.html>

* Jason Brownlee - How to Generate Random Numbers in Python, <https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/>

* John DeJesus - Hypergeometric Distribution Explained With Python, <https://towardsdatascience.com/hypergeometric-distribution-explained-with-python-2c80bc613bf4>

* Joshua Ebner - Numpy Random Seed Explained, <https://www.sharpsightlabs.com/blog/numpy-random-seed/>

* Jupyter Notebook - Markdown Cells, <https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html>

* Justin Bois - Lesson 23: Random number generation, <http://justinbois.github.io/bootcamp/2020/lessons/l23_random_number_generation.html>

* Lew Yerian - Understanding Permutations and Combinations, <https://www.isixsigma.com/community/blogs/understanding-permutations-and-combinations/#:~:text=Permutations%20are%20for%20lists%20(where,permutation%20is%20an%20ordered%20combination.&text=A%20true%20%E2%80%9Ccombination%E2%80%9D%20lock%20would,a%20true%20%E2%80%9Ccombination%E2%80%9D%20lock.>

* Manish Pathak - Probability Distributions in Python, <https://www.datacamp.com/community/tutorials/probability-distributions-python>

* Maths is Fun - The Binomial Distribution, <https://www.mathsisfun.com/data/binomial-distribution.html>

* Numpy Manual 1.19 - NumPy 1.19.0 Release Note - Changes, <https://numpy.org/doc/stable/release/1.19.0-notes.html#changes>

* Packt - NumPy random numbers, <https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781785285110/2/ch02lvl1sec16/numpy-random-numbers>

* RFunction.com - set.seed, <http://rfunction.com/archives/62>

* Royal Statistical Society - Notebook: The Laplace distribution, <https://rss.onlinelibrary.wiley.com/doi/full/10.1111/j.1740-9713.2018.01185.x>

* Rylan Fowers - Python Poisson Distribution - Numpy Random Poisson, <https://www.youtube.com/watch?v=dGhDzCJryGA>

* Sachin Date - The Poisson Process: Everything you need to know, <https://towardsdatascience.com/the-poisson-process-everything-you-need-to-know-322aa0ab9e9a>

* Science Direct - Hypergeometric Distribution, <https://www.sciencedirect.com/topics/mathematics/hypergeometric-distribution>

* Stack Exchange - What exactly is a seed in a random number generator?, <https://stats.stackexchange.com/questions/354373/what-exactly-is-a-seed-in-a-random-number-generator>

* Stack Exchange - Where in R code should I use set.seed() function (specifically, before shuffling or after)?, <https://stats.stackexchange.com/questions/215209/where-in-r-code-should-i-use-set-seed-function-specifically-before-shuffling>

* Tutorials Point - Statistics: Laplace Distribution, <https://www.tutorialspoint.com/statistics/laplace_distribution.htm>

* w3shools.com - Binomial Distribution, <https://www.w3schools.com/python/numpy_random_binomial.asp>

* w3shools.com - Random Numbers in NumPy, <https://www.w3schools.com/python/numpy_random.asp>

* w3shools.com - Random Permutations, <https://www.w3schools.com/python/numpy_random_permutation.asp>

* Will Koehrsen - The Poisson Distribution and Poisson Process Explained, <https://towardsdatascience.com/the-poisson-distribution-and-poisson-process-explained-4e2cb17d459>

* Wolfram Mathworld - Binomial Distribution,<https://mathworld.wolfram.com/BinomialDistribution.html>

* Wolfram Mathworld - Hypergeometric Distribution, <https://mathworld.wolfram.com/HypergeometricDistribution.html>

* Wolfram Mathworld - Laplace Distribution, <https://mathworld.wolfram.com/LaplaceDistribution.html>

* Wolfram Mathworld - Normal Distribution, <https://mathworld.wolfram.com/NormalDistribution.html>

* Wolfram Mathworld - Pseudorandom Number, <https://mathworld.wolfram.com/PseudorandomNumber.html>

* Yourbasic.org - What’s a seed in a random number generator?, <https://yourbasic.org/algorithms/random-number-generator-seed/>