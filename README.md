# house-price-prediction-ML
This repository is for the house price prediction project done using linear regression. <br>
Code explanation here ---> <br>
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import OneHotEncoder
from sklearn.metrics import mean_absolute_error
from sklearn.model_selection import train_test_split
from sklearn import svm
from sklearn.svm import SVC
from sklearn.metrics import mean_absolute_percentage_error
from sklearn.ensemble import RandomForestRegressor
from sklearn.linear_model import LinearRegression
```
The pandas library is imported as is aliased as pd, pandas is a python library used for data manipulation and data analysis in Python. <br>
The matplotlib.pyplot is imported and is aliased as plt, this is a python library used for data visualization. <br>
The seaborn library is imported and this is a library that is built on top of the matplotlib library. It provides more aesthetic options for data visualization. <br>
The OneHotEncoder is imported from the sklearn.preprocessing module, it is a preprocessing technique used to convert the categorical features into numerical values that can be worked and understood by the machine learning algorithms. <br>
The mean_absolute_error and the mean_absolute_percentage_error are imported from the sklearn.metrics module, these are certain evaluation metrics used for calculating the error and the accuracy of a regression model, this works by calculating the absolute differences between the predicted and the actual values. <br>
train_test_split is imported from the sklearn
