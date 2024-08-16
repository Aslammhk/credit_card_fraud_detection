💳**Credit-Card-Fraud-Detection**
This is a machine learning project made on Credit Card Fraud Detection. The data is taken from Kaggle. Different classification machine learning algorithms have been applied to get the maximum accuracy.

🚧**About Project**
The purpose of the project is to make a machine learning model that will be able to detect whether the transaction made is fraud or genuine based upoen the given parameters. The parameters used to calculate the whether the class is fraud or genuine, we are not given any information regarding the features of the dataset in order to maintain the privacy of the user.

📈**About The Dataset**
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

📈 **Dataset Link**
🏠 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

🤖 **Machine Learning Algorithms Used**

**Logistic Regression**
The method of modelling the probability of a discrete result given an input variable is known as logistic regression. The most frequent logistic regression models have a binary outcome, which might be true or false, yes or no, and so forth. Logistic regression is a handy analysis tool for determining if a fresh sample fits best into a category in classification tasks. Because components of cyber security, such as threat detection, are classification problems, logistic regression is a valuable analytic tool.

![image](https://github.com/Aslammhk/credit_card_fraud_detection/blob/main/Decision%20Trees.png)

**Decision Trees**
By constructing a decision tree, the decision tree classifier builds the classification model. Each node in the tree represents a test on an attribute, and each branch descending from that node represents one of the property's possible values. The training set's instances are categorised by navigating them from the root of the tree to a leaf, based on the results of the tests along the way. Each node in the tree splits the instance space into two or more sub-spaces based on an attribute test condition, starting with the root node. After that, the procedure is repeated for the subtree rooted at the new node, until all records in the training set have been processed.

![image](https://github.com/Aslammhk/credit_card_fraud_detection/blob/main/Decision%20Trees.png)

