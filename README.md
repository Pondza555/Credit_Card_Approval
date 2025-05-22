# Credit_Card_Approval
## data from kaggle https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data?select=application_record.csv
### 1. Understand the dataset
#### - Dataset contain many categorical data and less numerical data so I decided to use tree based model in this dataset which is XGBoost.
#### - I found 30% of data has NULL or NaN in one feature and has imbalance dataset, I fix NULL or NaN by drop that feature out due to I don't want to replace it with something because it will cause model to predict bad, I use SMOTE to fix imbalance dataset.
### 2. What is my objective?
#### - Create classification model to classify user who deserve approval.
#### - Focus on F1-score to balance between precision and recall.
### 3. What business get?
#### - Implement model to real scenarios to prevent wrong approval.
#### - Reduce non profit loan for business.
