# KIOS Graduate Summer School 2018

Summer school web site: [www.kios.ucy.ac.cy/summer-school/](http://www.kios.ucy.ac.cy/summer-school/)


## Introduction
- `Python` is one of the most popular programming languages used extensively in web development, as well as in science and engineering (including data science). In this course we will be using `Python 2.7`.
- `Jypyter` is a browser-based tool which allows us to interface with `Python` in an easy way. Jupyter is primarily used for educational purposes - not for development. We can create `notebooks` which we can share so that others can replicate our work and make changes.
- `Anaconda` is an environment which makes it easy to setup various languages and tools, such as `Python`. 


## Installation instructions

### On Windows

1. Download `Python 2.7 version` from the [Anaconda website](https://www.anaconda.com/download/). *Make sure you select the `2.7` version.* 
2. When prompted in instalation, select `Add Anaconda to my PATH environment variable` 
3. When installation has finished, run `Anaconda Prompt`. This will open a command line window in Windows.
4. Run the command `jupyter notebook`. This should open a local jupyter notebook.

Reference:
- [Installing Python on Windows](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444)

### On Linux/Unix

1. Download `Python 2.7 version` from the [Anaconda website](https://www.anaconda.com/download/)
2. Open a terminal and `cd` to the installation folder
3. Enter the `bin/` directory (at `anaconda-base-dir/bin`) and run `source activate root`; this will activate the `root` (default) Anaconda environment
4. Start the anaconda navigator by running `./anaconda-navigator`

Read [this tutorial](anaconda/README.md) on how to use the anaconda navigator.

## Python Packages

You may install the following packages using Anaconda:

- Numpy
- Scipy
- Scikit-learn
- CVXPy

**Classification exercise**: numpy, sklearn, matplotlib, seaborn, scipy

**Regression exercise**: numpy, pandas, sklearn, matplotlib, pydot, scipy

**System identification exercise**: numpy, matplotlib, cvxpy, scipy, (statsmodels)
**Notes:**

- If a package is not included in Anaconda read [this tutorial](anaconda/README.md) on how to install packages using the anaconda navigator, or use [conda](https://conda.io/docs/user-guide/tasks/manage-pkgs.html) in the terminal.
- Run this [notebook](anaconda/installation_test.ipynb) to test if the packages are installed succesfully.

## Prerequisites
Preparation material as follows:
- Python and Numpy [tutorial](http://cs231n.github.io/python-numpy-tutorial/#python)
- Juyter Notebook [tutorial](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46)
- Pandas [tutorial](https://pandas.pydata.org/pandas-docs/stable/10min.html)
- Scikit-learn [tutorial1](https://machinelearningmastery.com/a-gentle-introduction-to-scikit-learn-a-python-machine-learning-library/) and [tutorial2](http://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)
- CVXPy [tutorial](http://www.cvxpy.org/) (optional, since we will explain eveything in class)
