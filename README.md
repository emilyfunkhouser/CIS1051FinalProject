# CIS1051FinalProject

# Below is what needs to be installed/imported which can also be seen in the code itself: 

Install tensorflow 1.13.1 (version 2 of tensorflow will not work for this)

Install TFANN

import numpy as np

import matplotlib.pyplot as mpl

from sklearn.preprocessing import scale

from TFANN import ANNR

from google.colab import files

import statistics

import xlrd

Note: You must restart the runtime after installing tensorflow and before executing what is below. You can see the specific line this correponds to by viewing the jupyter notebook. 

Note: I have preprocessed Excel files that have to be uploaded using files.upload(). These files will be uploaded to GitHub.


# Issues along the way: 

I attempted to use iexfinance, but I was having issues involving tokens, etc. Thus, I ended up downloading Yahoo Finance data instead (4/26/16 - 4/26/21). 

Installing required modules (Needed to use older version of tensorflow, struggled trying to find a solution to this issue)

Order of executing statements (Needed to restart runtime after importing the old version of tensorflow for the code to work)

Preprocessing data (Skipped this step originally and had to research what the issue was)

Utilizing Google Colab notebooks (New skill I needed to adapt to learn)

When displaying the Final chart, I needed to get the price/dates back to their orginal values because they were standardized. I needed to multiply the values by the standard deviation and add the mean in order to show the true values. 

# Things I learned: 

Integrating Finance/coding into one project. 

Troubleshooting and dealing with errors. 

# What I enjoyed: 

The problem solving aspect of creating this project. 

Applying both Finance/CS knowledge.

Having created a simple stock predictor model that could definitely be expanded on the future as I explore more fintech concepts. 

# Youtube Link: 
https://youtu.be/UspyBjTN7TU
