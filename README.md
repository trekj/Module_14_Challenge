# Machine Learning Trading Bot

You’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## What You're Creating
You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.

# Conclusion

 **BASELINE MODEL**                     
                        
 **Precision**              -1(0.43), 1(0.56)                     

**Recall**                 -1(0.04), 1(0.96)   

**Accuracy**                                0.55 

**MACHINE LEARNING MODEL**

 **Precision**  -1(0.44), 1(0.56)
 
 **Recall**      -1(0.33), 1(0.66)

**Accuracy**                                0.52

Based on the results provided above, I will have to give more weight on accuracy and my overall conclusion is that the Baseline Model is slightly better than the alternative Machine Learning Model.

## Technologies
This project is written in Python 3.8 with the following libraries:

***panda*** -a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.

***numpy*** -is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python.

***sklearn*** -Scikit-Learn is a free machine learning library for Python. It supports both supervised and unsupervised machine learning, providing diverse algorithms for classification, regression, clustering, and dimensionality reduction. The library is built using many libraries you may already be familiar with, such as NumPy and SciPy. It also plays well with other libraries, such as Pandas and Seaborn.


## Installation Guide
Before running the application first install the following dependencies.

import pandas as pd

from pathlib import Path

import matplotlib.pyplot as plt

from sklearn import svm

from sklearn.preprocessing import StandardScaler

from pandas.tseries.offsets import DateOffset

from sklearn.metrics import classification_report

***Usage***
After cloning the repository, open the directory Starter Code and run the program by typing python machine_learning_trading_bot.ipynb

***Contributors***

James Tagapan

jtagapan@gmail.com

License

Licensed under the MIT License. Copyright 2020# Module_10_Challenge
