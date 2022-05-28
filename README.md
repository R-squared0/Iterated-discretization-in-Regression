# Iterated-discretization-in-Regression (DSE302-Course-Project)
The aim of this project is to be able to predict the semi-major axis (named as pl_orbsmax) of exoplanet orbits from the given data set consisting of 289 features and 17969 data points. As the data set contains many NAN values and shifted rows, we first need to clean it and handle to missing values in order to make the data use able. Since this problem is based on predicting a continuous target variable: pl_orbsmax, we initially expected to solve the problem using regression techniques. As would be discussed ahead in detail, we finally came up with the 'Iterated Target Variable Discretization' algorithm and turned our regression problem into a classification problem, to get the best possible performance. \


## Code files

1. `ANN_models.ipynb` : This code contains the architechture for ANN model.
2. `DSML Final Project Polynomial Regression Code.ipynb` : This code contains the polynomial regression model.
3. `DSML Final Project Regression Models Code.ipynb` : This code contains Linear Regression, DTR, RFR and SVR.
4. `DSML Final Project Data Cleaning Code.ipynb` : Code to clean the raw data for certain models.
5. `Iterated_Discretization_code.ipynb` : Code to implement our classification model named "Iterated Target Variable Discretization".

## Data File

1. `data file` : Folder specifically tailored for the `Iterated_Discretization_code.ipynb` file
