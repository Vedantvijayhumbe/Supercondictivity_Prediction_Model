# Supercondictivity_Prediction_Model
This repo deals with plotting conclusive derivations from the the Dataset (https://archive.ics.uci.edu/dataset/464/superconductivty+data) .
│── /Preprocessing 
│   ├──splitting data between train and test 

│── /Feature selection 

│   ├── select the the festure from train.csv we need to focus on such as critical temperature to derive our conclusions 

│── /Model selection 

│   ├── XGboost ( as used @ninad , but since the uci dataset does not have any missing values we would try RF(random forest) ) 

│── Predictions - Will take time ( would do it after complete understanding ) . 

│── 

│── .env  <-- import pandas as pd
  import numpy as np
  import matplotlib.pyplot as plt
  import seaborn as sns
  from sklearn.model_selection import train_test_split
  from sklearn.preprocessing import StandardScaler
  from sklearn.ensemble import RandomForestRegressor
  from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
  from sklearn.model_selection import train_test_split, cross_val_score, GridSearchCV
  from sklearn.preprocessing import StandardScaler
  
  from xgboost import XGBRegressor
  from sklearn.neural_network import MLPRegressor
  from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
