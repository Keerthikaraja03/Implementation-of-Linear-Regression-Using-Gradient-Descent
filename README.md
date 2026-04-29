# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Open google colab
2. type the program
3. run the program
4. we can see the output

## Program:
```
/*
Program to implement the linear regression using gradient descent.
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
data = pd.read_csv("Startup.csv")
X = data['R&D Spend'].values
y = data['Profit'].values
X = (X - X.mean()) / X.std()
m = 0
b = 0
learning_rate = 0.01
epochs = 1000
n = len(X)
for i in range(epochs):
    y_pred = m * X + b
    dm = (-2/n) * np.sum(X * (y - y_pred))
    db = (-2/n) * np.sum(y - y_pred)
    m = m - learning_rate * dm
    b = b - learning_rate * db
print("Slope (m):", m)
print("Intercept (b):", b)
y_pred = m * X + b
plt.scatter(X, y)
plt.plot(X, y_pred)
plt.xlabel("R&D Spend (Normalized)")
plt.ylabel("Profit")
plt.title("Gradient Descent on 50_Startups Dataset")
plt.show()
Developed by: KEERTHIKA R
RegisterNumber: 212225040187 
*/
```

## Output:
<img width="1052" height="804" alt="Screenshot 2026-04-29 152350" src="https://github.com/user-attachments/assets/c59b896d-bb84-47d5-aadf-04e23bbcefb9" />


## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
