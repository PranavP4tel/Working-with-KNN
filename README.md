# K-Nearest Neighbors (KNN) for Classification
This repository contains two separate notebooks employing K-Nearest Neighbors (KNN) classification models for the following purposes:

1. Mushroom Edibility Classifier: Classifies mushrooms as edible or poisonous.
2. Diabetes Prediction Model: Classifies whether a patient has diabetes based on medical features.
</hr>

### 1. Mushroom Edibility Classifier
This model predicts whether a mushroom is edible or poisonous based on various features cap-diameter, gill-attachment, gill-color, stem-color and more. 

The following tasks were conducted:
a. Data exploration to evaluate the dataset with the various features to be used for classification
b. Scaling the features values
c. Splitting the dataframe for training and testing
d. Creating the classifier and testing it for accuracy
e. Hyperparameter tuning using Grid Search CV
f. Obtaining feature relevance score to understand the most important features for classification
g. Training the model on only the most relevant subset of features 

<b>Conclusion</b>: If we were to train the model on a subset of the features the model accuracy drops. Hence, we include all the variables and obtain a KNN classifier for the problem with an accuracy score of 98.77%.
</hr>

### 2. Diabetes Existence Classifier
This model classifies an individual as one having diabetes or not, based on their medical information such as Cholesterol, Glucose, Age, Gender, BMI, HDL Chol, Chol/HDL ratio and more.

The following tasks were conducted:
a. Data exploration to evaluate the dataset with the various features to be used for classification
b. Feature selection and scaling
c. Splitting the dataframe for training and testing
d. Creating the classifier and testing it for accuracy
e. Hyperparameter tuning using Grid Search CV to obtain the best accuracy score
f. Obtaining feature relevance score to understand the most important features for classification
g. Balancing the dataset with respect to the target variable 
h. Training the model on only the most relevant subset of features, with the optimal hyperparameter value

<b>Conclusion</b>: By choosing the feature with the highest f-score and the appropriate hyperparameter value (obtain using cross validation), we have a KNN Classifier that has 95% accuracy!

The models are implemented using scikit-learn in Python. Any feedback or suggestions would be highly appreciated!
