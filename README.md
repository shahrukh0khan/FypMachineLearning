# Customer Order-In Propensity Prediction 
This project is based upon building and experimenting machine learning models to calculate and predict customer Order-in propensities and Collection propensities for different products at various stores. 
#### Machine learning models used:
* Linear Regression
* LASSO
* Ridge
* Random Forest Regressor
* XGBoost Regressor

These prediction models are used to 
predict propensity of order-in and collection at stores on a sample of 1,000,000 rows of 
randomly selected historic product data. Data pre-processing, hyperparameter tuning of models and experimentation 
with different combinations of attributes are done to attain better accuracy. 

The model accuracies are compared and XGBoost is selected finally for predictions as 
it performs better than the rest with RMSE value of 0.3631 for predicting order-in propensities. The 
model accuracy decreases and error increases when predicting collection propensities. It is observed 
that including demand units in training data as input increases the models performance.
