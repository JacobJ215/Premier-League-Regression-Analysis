# Premier League Regression Analysis

### Overview

In this repo you will find two notebooks exploring the basics of  linear regression analysis. Here we are working with the [Premier League dataset](Data/EPL_Soccer_MLR_LR.csv), where the goal is to predict  the the score of a Scocer player given various features. 

**Notebook 1** [Simple Linear Regression](simple_regression.ipynb) utilizes a univariate statsmodels `sm.OLS()` model to  solve this problem, while **Notebook 2** [Multi-Linear Regression](multiple_linear_regression.ipynb) uses a multivariate approach while implementing both the statsmodels `sm.OLS()` and Scikit_Learn's `LinearRegression()`, where the model is evaluated against the R-Squared and Root Mean Squared error.

### Install necessary libraries 

``` python 
!pip install numpy==1.21.2
!pip install seaborn==0.11.1
!pip install matplotlib==3.4.3
!pip install statsmodels==0.12.2
!pip install pandas==1.2.4
!pip install scipy==1.6.3
!pip install scikit_learn==0.24.2
!pip install plotly==5.11.0
```