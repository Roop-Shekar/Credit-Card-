   #  CREDIT CARD FRAUD DETECTION README 

##PROJECT TITLE: Credit Card Fraud Detection
##DATASET LINK: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 
                           
##DESCRIPTION:
 The concept of credit card fraud is also a major issue in the digital economy, as online-based systems of payment are developing fast. Conventional rule-of-thumb systems are not up to date the dynamic nature of patterns of fraud results in a false positive. In this project, the machine learning pipeline is applied with the issues of massively unbalanced data datasets and prediction interpretability effectively addressed.
 
##METHODOLOGY:
###Data pre-processing: The StandardScaler tool of scikit-learn was used to standardise the metadata of Time and Amount, which normalises these data and reduces bias associated with two features that have unequal scales.

###Train-test split: The data were divided into a training (80 0-percent) and testing (20 0-percent) were split. A stratified division has been used to make sure that the frequency of the fraudulent transaction is the same in both sets. 

###Dealing with the class imbalance: There was the application of SMOTE on training data only. This method will create artificial examples of the minority (fraud) category to come up with a balanced dataset to train models without the leakage of test data. 

###Model training: There are five trained supervised learning models that were selected on the balanced set: logistic regression, decision tree, random forest, XGBoost, and one popular support vendor classifier (SVC). 

######Model evaluation and interpretation: The models would be evaluated on the unseen test set on a complete set of measures. Visualisations of feature-importance and SHAP values summative were created in order to explain the factors that had the most bearing in the models prediction.

##Machine Learning Models Used:
 Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Support Vector Classifier (SVC)

##RESULTS:
Accuracy: approximately 99.9%
Precision: between 0.82 and 0.91
Recall: between  0.88 to 0.93
F1-Score: between  0.85 to 0.92

##USAGE:
Open Jupyter Lab(or Jupyter Notebook) and open the main notebook to run the .ipynb file in it .Run the  cells  in a sequence.

##CONTACT:
Author: Roop Shekar Veeranki
