# House Prices EDA and Prediction


**Introduction**

The enclosed Jupyter Notebook contains the analysis of a dataset describing many aspects of residential homes. The notebook uses machine learning models to predict final house prices based on relevant features, such as overall quality, house area, etc.

**Problem Statement**

Can we predict final prices of houses based on relevant features? 


**Approach**

First, I conducted an exploratory data analysis to gain insight into the data. I also checked for and imputed missing data and did feature engineering. I created new features and reduced the number of features to minimise noise. I implemented several machine learning algorithms including Multiple Linear, Ridge and Lasso Regression, Elastic Net, Decision Tree and Random Forest Regressors, and KNN. I also used an ensemble method – a Voting Regressor – to combine results from the previous models. 

**Results**

I had the best result using ridge regression, which had an RMSE score of 0.14443 based on the test dataset.
