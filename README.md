# FCFA-SWIFT Python training 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leifdenby/FCFA-SWIFT-Python-2021/HEAD)

Hi!

You're looking at the repository for the 7th to 12th June 2021 FCFA
African-SWIFT Python training course.

The repository contains all the Jupyter notebooks which make up the course
training material (including example answers to the exercises)

## Course overview

The course time-table is below (note: all times are in local-time in
Ghana, so UTC+0)

<img src="graphics/timetable-white.png" width=500 />



The course is taught over a number of sessions, with each session introducing a new set of topics. Each session has an associated Jupyter notebook (see below) which contains background information introducing you to the topic and a set of exercises for you to work through.

- Monday:
  
  - numpy and matplotlib (using CSV, ASCII and XLXS files): [numpy_matplotlib.ipynb](notebooks/numpy_matplotlib.ipynb)

- Tuesday:
  
  - numpy, matplotlib & cartopy: [numpy_matplotlib_cartopy.ipynb](notebooks/numpy_matplotlib_cartopy.ipynb)
  
  - pandas: [pandas.ipynb](notebooks/pandas.ipynb)

- Wednesday:
  
  - pandas (with seaborn): [pandas_seaborn_.ipynb](notebooks/pandas_seaborn_.ipynb)
  
  - xarray (subsetting data): [xarray_part1.ipynb](notebooks/xarray_part1.ipynb)

- Thursday:
  
  - xarray (grouping data): [xarray_part2.ipynb](notebooks/xarray_part2.ipynb)
  
  - xarray + cartopy: [xarray_cartopy.ipynb](notebooks/xarray_cartopy.ipynb)

- Friday:
  
  - xarray + metpy: [xarray_metpy.ipynb](notebooks/xarray_metpy.ipynb)
  
  - xarray + cartopy: [xarray_xclim.ipynb](notebooks/xarray_xclim.ipynb)

All notebooks are stored in [notebooks/](notebooks/). There are also a set of sample answers for each exercise in [notebooks__sample_answers/](notebooks__sample_answers/) - but wait to look at this until after you've completed the course :)

## Getting started

To work through the course you will need three things on your computer:

1. A copy of the course Jupyter notebooks
2. A copy of the datasets we’ll be working with
3. A conda environment with the necessary packages installed

If you are having difficulty getting set up on your own computer you may
click the "launch on binder"-link above. **Note**: when you run the
exercises on binder what you write will not be saved locally and so you
will loose your work if you close the browser. 

### 1. Downloading the notebooks to your computer

The easiest way to get a copy of the notebooks on your computer is simply to clone this repository

```bash
$> git clone https://github.com/leifdenby/FCFA-SWIFT-Python-2021/
$> cd https://github.com/leifdenby/FCFA-SWIFT-Python-2021/
```

### 2. Download the datasets to your computer

All the datasets used in this course are in a single zip-file that you can download from [http://homepages.see.leeds.ac.uk/~earlcd/fcfa-swift-python-2021/fcfa-swift-python-2021.data.zip](http://homepages.see.leeds.ac.uk/~earlcd/fcfa-swift-python-2021/fcfa-swift-python-2021.data.zip). You should unpack this file to the same folder where you cloned the course notebooks repository:

```bash
$> wget http://homepages.see.leeds.ac.uk/~earlcd/fcfa-swift-python-2021/fcfa-swift-python-2021.data.zip
$> unzip fcfa-swift-python-2021.data.zip
```

### 3. Setting up a conda environment

To install the python packages you will be taught to use in this course you can use the conda "environment-file" included in the course repository (it's called `environment.yml`). First make sure you have `conda` installed on your computer ([instructions on how to install conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html))

```python
$> conda env create -n fcfa-swift -f environment.yml
$> conda activate fcfa-swift
```

You can now open up a Jupyter notebook session and get working on the notebooks.

```bash
$>jupyter notebook
```

We hope you enjoy the course!  
Marian, Maureen, Jeffrey and Leif
 

| ![](graphics/fcfa_logo.jpg) | ![](graphics/swift-logo.png) |
| --------------------------- | ---------------------------- |


