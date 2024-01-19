# Wine_Classification
Built wine classification models leveraging wine chemical data from Databricks in AWS. 

Based on the results of the EDA the following predictors were selected: 
* volatile acidity
* residual sugar
* chlorides
* free sulfur dioxide
* total sulfur dioxide
* density

The average value, maximum value, minimum value, and histograms of each of the predictors grouped by wine type shows that these values appear to significantly differ by wine type.

Different versions of a logistic regression model and random forest model were built.
Performance metrics were compared and it was determined the random forest was the appropriate classification model for the purspoe of this project, wine classifcation, with an accuracy score of 99.7%.
