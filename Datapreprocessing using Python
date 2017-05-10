# Data preprocessing in Machine learning using Python
# library import
import numpy as np
import matplotlib.pyplot as plt
import panda as pd

# Dataset import
dataset = pd.read_csv('input_file.format')
x = dataset.iloc[independent variable].values
y = dataset.iloc[independent variable].values

# Creating dummmy values for missing data
from sklearn.preprocessing import Imputer
imputer = Imputer(missing_values = 'NAN', strategy = 'mean', axis = 0)
imputer = imputer.fit(x[independent variable])
x[independent variable] = imputer.transform(x[independent variable])

# Categorizing the input data
from sklearn.preprocessing import LabelEncoder
labelencoder_x = LabelEncoder()
x[column need to categorize] = labelencoder_x.fit_transform(x[column need to categorize])
onehotencoder = OneHotEncoder(categorical_fetures=[0])
x = onehotencoder.fit_transform9x).toarray()

# Splitting the dataset 
from sklearn.cross_validation import train_test_split 
x_train, x_test, y_train, y_test = train_test_split(x,y,test_size = 0.2, random_state = 0)

# scaling the data in the dataset
from sklearn.cross_validation import StandardScaler
sc_x = StandardScaler()
x_train = sc_x.fit_transform(x_train)
x_test = sc_x.transform(x_test)
