# Credit Card Fraud Detection using GUI App deployment

## Download the Dataset from here -
kaggle datasets download -d mlg-ulb/creditcardfraud

## Or you can download directly from this link and read in any .ipynb supported IDE -
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Description -
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## To run the GUI App follow this commands :-
### 1. Download the pickle (.pkl) file and load it in your working directory.
### 2. Download the Credit_Card_Fraud_Detection_Deployment file and host in in any local server preferably VS Code or jupyter notebook.(Beware this file wont work in Colab or Kaggle notebooks).
### 3. Run all the cells and a GUI App (dialog box) will appear.
### 4. Fill all the rows and click on predict button to check whether it is a normal transaction or fraud transaction.
