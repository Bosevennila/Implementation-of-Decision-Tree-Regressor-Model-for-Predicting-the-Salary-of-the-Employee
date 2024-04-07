# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the libraries and read the data frame using pandas.
2. Calculate the null values present in the dataset and label encoder.
3. determine test and training data set and apply decision tree regression in dataset.
4. calaculate Mean square error,data prediction and r2.

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: 
RegisterNumber:
import pandas as pd
data=pd.read_csv("/content/Salary.csv")
data.head()

data.info()

data.isnull().sum()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data['Position']=le.fit_transform(data['Position'])
data.head()

x=data[['Position','Level']]
y=data['Salary']

x=data[['Position','Level']]
y=data['Salary']

from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier()
dt.fit(x_train,y_train)
y_predict=dt.predict(x_test)

from sklearn import metrics
mse=metrics.mean_squared_error(y_test,y_predict)
mse

r2=metrics.r2_score(y_test,y_predict)
r2

dt.predict([[5,6]])

*/
```

## Output:
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/d81e3f57-a2e0-4fa4-b57d-80f539f411aa)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/bf28f31b-7c20-486d-9783-eb3d89b721ce)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/859f0027-a69f-407a-af32-3eb47415d40c)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/535c3da5-c4dd-4fb7-a2a5-4933a15ca71f)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/366dd3c4-1262-4364-b3e1-c4f8b2b82acd)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/2488f329-18b0-4867-b67d-b945da2ef6f3)
![image](https://github.com/AkilaMohan/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144870486/1b8a79f8-7aa8-4f54-bff8-1a9e14ac7a83)



## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
