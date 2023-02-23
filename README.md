# CA-04

CA 04 - Ensemble Methods
Dataset Description:

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset:

• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]

• Number of attributes (Columns): 7

• Number of instances (Rows): 48,842

Necessary Packages:

import pandas as pd
import numpy as np
import sklearn
import sklearn.metrics as metrics
import matplotlib.pyplot as plt
from sklearn import tree
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import roc_auc_score
from sklearn.ensemble import AdaBoostClassifier
from sklearn.metrics import accuracy_score
from sklearn.ensemble import GradientBoostingClassifier 
from sklearn.datasets import make_classification
from sklearn.model_selection import cross_val_score

Data Source:

url = 'https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true'
