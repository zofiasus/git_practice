Hello Git and GitHub

The code in this repository is various projects that utilize machine learning in Python.

DRUG RESISTANCE PROJECT
My first project is in the drug_resistance_classification_project.py file.
This project uses the https://www.kaggle.com/datasets/aliabedimadiseh/taxol-drug-resistance-cell-lines-in-breast-cancer/data dataset
Aim: to classify the cells into four types: BAS, HS578T, MCF7 and MDA-MB-231 based on the p values, and logFC values.
p-value: Compared between control and drug resistance cell
logFC: Fold change shows up or down regulations in the gene
The data was obtained through gene expression analysis using R in each of the datasets, which was between control and drug-resistant cells.
Three different machine learning models were tested to obtain the best result: Logistic Regression, Random Forest Classifier and AdaBoost Classifier
Random Forest Classifier proved best and hyperparameter (max_depth and n_estimators) tuning was done to optimize the classifier further.
Result: The optimal max_depth=12 and n_estimators=150, giving a final accuracy score of 73.2% on the testing set :)
