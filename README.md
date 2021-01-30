# credit_card_fraud

The objective of the project is to understand the Frauds in Credit Card Transactions. 

# Dataset
 
 The Dataset is from Kaggle. 
 Source : https://www.kaggle.com/mlg-ulb/creditcardfraud
 
The dataset contains transactions of European Card Holder from September 2013, 284,807 transactions and out of which ther are 492 fraud. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
 
It only includes numerical input variables that are the product of a transformation of a PCA. Unfortunately, we do not have original features and more context details about the data because of confidentiality concerns. Characteristics V1, V2,... The key components obtained with PCA are V28, 'Length' and 'Amount' are the only features not transformed with PCA. The 'Time' feature in the dataset, seconds have elapsed between each transaction and the first transaction. The 'Number' function is the Amount transaction, which can be used for example-dependent cost-sensitive learning. The answer variable is the 'Class' function, which takes value 1 in case of fraud and 0 otherwise.


# Analysis

The following techniques were implemented :
1. Cross-Validation
2. Oversample minority class (i.e. fradulent transactions)
3. Normalization of variables
4. Bagging
5. Boosting (XGBoost, ADABoost)
6. Ensemble modelling (Random Forrest)
7. Changing Threshold

# Conclusion

We found out that the oversampling (SMOTE) approach is ideally suited for our study of all the techniques we tried. Important high F1, precision and recall scores are observed in the accuracy score at a cost of a slight decrease. 
Thus, banks can better detect fraudulent transactions using the oversampling(SMOTE) model.

