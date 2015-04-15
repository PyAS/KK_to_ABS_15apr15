# KK's Rscript to Pyscript

Somayaji made a script in R which I am dying to reproduce in python using pandas and other great frameworks. His source file is:

> `-rwxrwx--- 1 root plugdev 1932 Apr 15 16:09 ProjectProposal.R*`

And the Resource for this learning is 
* _(This list may be continuously updated!)_

> __Data Analysis with Python Pandas
> [Source](https://bitbucket.org/hrojas/learn-pandas)__

And, my Notebook which is a copy of the same tutorial in a notebook, whose file name is `pandas_tutorial_3mar15.ipynb` and can be found in SageMath Cloud.

## Begin with this:

`from pandas import DataFrame, read_csv`
`import matplotlib.pyplot as plt`
`import pandas as pd`
`import sys`
`%matplotlib inline`

## Test your imports with this:

`print 'Python Version ' + sys.version`
`print 'Pandas Version ' + pd.__version__`

## And, Have fun!
