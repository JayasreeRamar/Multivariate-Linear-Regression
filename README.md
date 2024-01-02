# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
<br>import pandas as pd.

### Step 2:
<br>Read the csv file.

### Step 3:
<br>Get the value of X and Y variables.

### Step 4:
<br>Create the linear regression model and fit.

### Step 5:
<br>Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.

### step 6:
<br>Print the predicted output.

## Program:
```
# Multivariate Linear Regression
# Developed by: Jayasree R
# Register number: 23009250
import pandas as pd
from sklearn import linear_model
df=pd.read_csv('cars (1).csv')
a=df[['weight', 'Volume']]
b=df[['CO2']]
regr-linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient", regr.coef_)
print("Intercept:", regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## OUTPUT
![OUTPUT](<Screenshot 2024-01-03 004649.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.