The objective of this project is to predict Interest rate for the applicants based on values of variables loan purpose, duration, FICO score, balance and several others. 
The data is collected from kaggle.com and has 2 .csv file: loan_data_train.csv and loan_data_test.csv 
loan_data_train is the data for training purpose where all the variables are present. 
loan_data_test has all the variables except interest rate, that will be predicted by training and validating the model on train data and then deploying it on test data. 
3 model are used: Linear regression, Lasso Regression, Ridge Regression The r2 score for Linear regression, Lasso Regression and Ridge Regression are 0.76, 0.77 and 0.77. All 3 model have quite similar performance.
