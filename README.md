# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Read the data from the CSV file 

### Step2
Extract features and target variables.

### Step3
Initialize and fit the linear regression model.

### Step4
Print the coefficients and intercept

### Step5
Predict CO2 emission for given weight and volume.

## Program:
## Developed By : VASANTH N
## Register Number : 24000697

        import pandas as pd        
        from sklearn import linear_model       
        df pd.read_csv("carsemission.csv")    
        X df[['Weight', 'Volume']]    
        y = df['C02']      
        regr linear_model.Linear Regression()       
        regr.fit(X, y)       
        print('Coefficients:', regr.coef_)       
        print('Intercept:', regr.intercept_)
        predictedC02 regr.predict([[3300, 1300]])
        print('Predicted CO2 for the corresponding weight and volume', predictedC02)

## Output:
![Screenshot 2024-12-13 182447](https://github.com/user-attachments/assets/fb9f1f1d-1070-440d-a2a2-df94dbc5615d)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
