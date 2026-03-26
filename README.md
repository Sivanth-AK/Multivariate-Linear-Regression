# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
import pandas as pd.
### Step2
<br>
Read the csv file.
### Step3
<br>
Get the value of X and y variables
### Step4
<br>
Create the linear regression model and fit.
### Step5
<br>
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.
## Program:

```
Developed by:SIVANTH T
Register Number:212225240150
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))
```
## Output:


### Insert your output

<br>
<img width="1418" height="354" alt="image" src="https://github.com/user-attachments/assets/a5018f8b-460c-4987-9f53-21970a9eb589" />
## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
