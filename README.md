# EuroScipy 2015 Pandas Tutorial

[![Join the chat at https://gitter.im/jorisvandenbossche/2015-EuroScipy-pandas-tutorial](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jorisvandenbossche/2015-EuroScipy-pandas-tutorial?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repository contains the material (notebooks, data) for the pandas tutorial at EuroScipy 2015.

## Requirements to run this tutorial

To follow this tutorial you need to have the following packages installed:


- Python version 2.6-2.7 or 3.3-3.4
- `pandas` version 0.15.2 or later: http://pandas.pydata.org/
- `numpy` version 1.7 or later: http://www.numpy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `ipython` version 3.x with notebook support, or `ipython 4.x` combined with `jupyter`: http://ipython.org
- `seaborn` (this is used for some plotting, but not necessary to follow the tutorial): http://stanford.edu/~mwaskom/software/seaborn/

I recommend to use the [conda](https://store.continuum.io/) environment manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (very large) Anaconda software
distribution, found at http://continuum.io/downloads).

Once this is installed, the following command will install all required packages in your Python environment:
```
conda install pandas jupyter seaborn
```

But of course, using another distribution (e.g. Enthought Canopy) or pip is good as well, as long
as you have the above packages installed.


## Downloading the tutorial materials

If you have git installed, you can get the material in this tutorial by cloning this repo:

    git clone https://github.com/jorisvandenbossche/2015-EuroScipy-pandas-tutorial.git

As an alternative, you can download it as a zip file:
https://github.com/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/archive/master.zip.
I will probably make some changes until the start of the tutorial, so best to download
the latest version then (or do a `git pull` if you are using git).

Two data files are not included in the repo, you can downloead them from: [`titles.csv`](https://drive.google.com/file/d/0B3G70MlBnCgKa0U4WFdWdGdVOFU/view?usp=sharing) and [`cast.csv`](https://drive.google.com/file/d/0B3G70MlBnCgKRzRmTWdQTUdjNnM/view?usp=sharing) and put them in the `/data` folder.

## Content

To view the content on nbviewer:

- [Index](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/Index.ipynb)
- [01 - Introduction](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/01%20-%20Introduction.ipynb)
- [02 - Data structures](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/02%20-%20Data%20structures.ipynb)
- [03 - Indexing and selecting data](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/03%20-%20Indexing%20and%20selecting%20data.ipynb)
- [03b - Some more advanced indexing](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/03b%20-%20Some%20more%20advanced%20indexing.ipynb)
- [04 - Groupby operations](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/04%20-%20Groupby%20operations.ipynb)
- [05 - Time series data](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/05%20-%20Time%20series%20data.ipynb)
- [06 - Reshaping data](http://nbviewer.ipython.org/github/jorisvandenbossche/2015-EuroScipy-pandas-tutorial/blob/master/06%20-%20Reshaping%20data.ipynb)


