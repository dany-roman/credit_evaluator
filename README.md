# Predicting Credit Risk



## Objective

Create a machine learning model that attempts to predict whether a loan from will become high risk or not using Logistic Regression and Random Forest Classifier.



## Approach

- Used 2019 loan data to predict the credit risk of loans from the first quarter of the following year (2020).

- Data was preprocessed by converting categorical data to numeric/binary columns. Columns that did not exist in both training and set data were removed.

- Loaded (fit) training data, training target data, testing data, and testing target data into logistic regression and random forest classifier models.
- Models were scored using both training and data set.
- Scaled data and target data were loaded into logistic regression and random forest classifier. Models were scored again using scaled data.



## Predictions

- Random forest classifier will perform better than logistic regression under scaled and unscaled data sets.
- Scaling will increase in the accuracy of both logistic regression and random forest classifiers. 



## Results

Random forest classifier performed better than logistic regression using unscaled data; however, there was a 12% reduction in accuracy when using scaled data compared with unscaled data.

Logistic regression performed far better using scaled data compared with unscaled data. 

Both random forest and logistic regression performed equally using scaled data.

Both models would likely perform better by reducing the number of data columns.



*Logistic Regression - Unscaled data*

- Training Data Score: 65%
- Testing Data Score: 52%



*Logistic Regression - Scaled data*

- Training Data Score: 99%
- Testing Data Score: 54%



*Random Forest - Unscaled data*

- Training Data Score: 99%

- Testing Data Score: 62%

  

*Random Forest - Scaled data*

- Training Data Score: 99%
- Testing Data Score: 54%


