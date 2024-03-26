# capstone-project-Data-science-bootcamp
This Capstone project is aimed at predicting the machine breakdown by identifying the anomalies in the data.
The data contains about 18000+ rows collected over few days. The column ‘y’ contains the binary labels, with 1 denoting there is an anomaly. The rest of the columns are predictors.  
correlation between predictor variables was checked and closely related values were removed. 
Feature selection was conducted and then Linear regression model was created using selected features.
Cross validation is conducted using Kfold method.
Hyperparameter tunning was also conducted using grid search cv
The output shows that gradient boosting technique is the best method for model building for such data.
