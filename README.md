# Heart-Disease-Classification
## About dataset
The dataset named "Cleveland Heart Disease Dataset" originates from the UCI Machine Learning Repository. The dataset was split in two: a training and a testing set. The task is to get the best predictor and guess if a patient has a heart disease.
https://archive.ics.uci.edu/ml/datasets/heart+disease
## 
![1149a8d7-1c36-45c7-879a-a0a364dbfe22](https://user-images.githubusercontent.com/79249217/219585977-089a8d7d-96d9-4b7d-87d6-e090d83a93e9.png)
## About models
After performing some EDA, I try to compare the accuracy of 3 models: LogisticRegression, KNeighborsClassifier, RandomForestClassifier
![e3a3663f-01c6-4574-8ee9-a57d3ced252d](https://user-images.githubusercontent.com/79249217/219586418-1b288b4c-e991-448d-b853-d2ef16d43b44.png)
For hyperparameter tuning, I try RandomizedSearchCV for LogisticRegression and RandomForestClassifier and I conclude that for this dataset RandomForestClassifier is the best model to use.
