# CIS1051FinalProject

# Below is what needs to be installed/imported which can also be seen in the code itself: 

Install tensorflow 1.13.1

Install TFANN

import numpy as np

import matplotlib.pyplot as mpl

from sklearn.preprocessing import scale

from TFANN import ANNR

from google.colab import files

import statistics

import xlrd


# Issues along the way: 

Installing required modules (Needed to use older version of tensorflow, struggled trying to find a solution to this issue)

Order of executing statements (Needed to restart runtime after importing the old version of tensorflow for the code to work)

Preprocessing data (Skipped this step originally and had to research what the issue was)

Utilizing Google Colab notebooks (New skill I needed to adapt to learn)

When displaying the Final chart, I needed to get the price/dates back to their orginal values because they were standardized. I needed to multiply the values by the standard deviation and add the mean in order to show the true values. 
