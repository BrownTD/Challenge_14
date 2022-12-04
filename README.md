# Challenge_14

For this challenge I am assuming the role of a financial advisor at one of the top five financial advisory firms in the world. Our firm is constantly competing with other firms to manage and automatically trade assets in a highly dynamic environment. My job is to improve the existing algorithmic trading systems to maintain the firms competitive advantage in the market.

In the machine_learning_trading_bot.ipynb file I am tasked with implementing an algorithmic trading strategy that uses machine learning to automate the trading decisions. I am also tasked with adjusting the input parameters to optimize the trading algorithm. Lastly, I am to train a new machine learning model and compare its perfermance to that of the baseline model.

The attempt to optimize the baseline model ended up with a 3% lower accuracy score. The attempt had similar precision scores, and the recall/f1 scores improved and declined mildly in opposite categories. The attempy to optimize the model using linear regression was ultimately a fail.

# Technologies

This project utilizes the following packages:

- Pandas 
- scikit-learn
- Hvplot 
- Numpy

# Installation Guide

Install the following dependencies before running the application.

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.svm import SVC
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

# Contributors

Nevyn Brown

# License

MIT
