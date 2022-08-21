# Detecting-Parkinsons-Disease
## Aim: To build a model to accurately detect the presence of Parkinson’s disease in an individual.
## About: 
### Parkinson’s Disease
* Parkinson’s disease is a progressive disorder of the central nervous system affecting movement and inducing tremors and stiffness.
### Libraries used 
* XGBoost is an open-source software library which provides a regularizing gradient boosting framework
### Dataset Used
* The UCI ML Parkinsons dataset has 24 columns and 195 records and is only 39.7 KB.
### Classification Model
* The XGBClassifier stands for eXtreme Gradient Boosting Classifier, which is a boosting algorithm based on gradient boosted decision trees algorithm and is a scikit-learn API compatible class for classification.
## Procedure:
* Load the data, extract features and labels from it.
* Initialize a MinMaxScaler and scale the features to between -1 and 1 to normalize them.
* Split the dataset into training and testing sets keeping 20% of the data for testing.
* Initialize an XGBClassifier and train the model.
* Calculate the accuracy of the model.
##  Conclusion:
Successfully detected the presence of Parkinson’s Disease in individuals using XGBClassifier for this and made use of the sklearn library to prepare the dataset The model delivered an accuracy of 94.87%.
