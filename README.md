# titanic_dataset-kaggle
#### Accuracy 78.7% 
#### Rank: 5009 out of 41428
#### Result can be improved by using ensemble of classifiers 
## Steps Taken
#### 1. Data Analysis and Data Cleaning
* Check for Missing Values
* Duplicate detection
* Outlier Detection
* Encoding of Categorical variables using Binary encoding and One-Hot encoding
* Checked Corelation of features
* Data distribution, later verified with validation data
#### 2. Data Split
* 10-fold cross validation 
* Train-test split (80-20 split)
Here test split actually means Train -validation split. Unlabelled Test data is provided by Kaggle.
#### 3. Modelling
* Logistic Regression
* k-Nearest Neighbors
* Decision Tree
* SVM
* Naive Bayes
* Random Forest
#### 4. Model Selection
* Best accuracy is given by Random Forest, but it is showing Low Bias and High Variance. Hence it will not generalize on the unseen dataset.
* Naive Bayes showed good test accuracy, but the training accuracy was less, which implies high bias. i.e the model trained is not robust enough to produce an accurate prediction
* Next best accuracy is given by Decision Tree of depth 5, with low Bias and Variance. Hence it came out to be the best classifier.
#### 5. Test Data Analysis and Data Cleaning
* Both the train and test(validation) data have same distribution. Hence we can say that train and validation data comes from the same source and the model created. It should work well for the unseen test data.
#### 6. Prediction 
