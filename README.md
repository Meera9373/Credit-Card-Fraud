# Credit-Card-Fraud
## Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
## Percentage of Not Fraud transaction Data
percentage of total not fraud transaction in the dataset:  99.82725143693798
## Percentage of Fraud transaction Data
percentage of total fraud transaction in the dataset:  0.1727485630620034
## Fraud transaction vs Non-Fraud transaction/
![image](https://user-images.githubusercontent.com/60151306/152281727-40bf0e3c-60c6-47f8-baf7-c7c6be3ca500.png)
## Amount Distribution Curve:
![image](https://user-images.githubusercontent.com/60151306/152281809-ebd48fbd-c904-4212-9a4e-41cf4e95a89b.png)



