# K-Nearest Neighbors (KNN) for Classification
This repository contains two separate notebooks employing K-Nearest Neighbors (KNN) classification models for the following purposes:

1. Mushroom Edibility Classifier: Classifies mushrooms as edible or poisonous.
2. Diabetes Classification Model: Classifies whether a patient has diabetes based on medical features.

</br>

### 1. Mushroom Edibility Classifier
This model predicts whether a mushroom is edible or poisonous based on various features cap-diameter, gill-attachment, gill-color, stem-color and more. 

The following tasks were conducted: </br>
a. Data exploration to evaluate the dataset with the various features to be used for classification </br>
b. Scaling the features values </br>
c. Splitting the dataframe for training and testing </br>
d. Creating the classifier and testing it for accuracy </br>
e. Hyperparameter tuning using Grid Search CV </br>
f. Obtaining feature relevance score to understand the most important features for classification </br>
g. Training the model on only the most relevant subset of features  </br>
 
<b>Conclusion</b>: If we were to train the model on a subset of the features the model accuracy drops. Hence, we include all the variables and obtain a KNN classifier for the problem with an accuracy score of 98.77%.
</br></br>

### 2. Diabetes Existence Classifier
This model classifies an individual as one having diabetes or not, based on their medical information such as Cholesterol, Glucose, Age, Gender, BMI, HDL Chol, Chol/HDL ratio and more.

The following tasks were conducted: </br>
a. Data exploration to evaluate the dataset with the various features to be used for classification </br>
b. Feature selection and scaling </br>
c. Splitting the dataframe for training and testing </br>
d. Creating the classifier and testing it for accuracy </br>
e. Hyperparameter tuning using Grid Search CV to obtain the best accuracy score </br>
f. Obtaining feature relevance score to understand the most important features for classification </br>
g. Balancing the dataset with respect to the target variable</br>
h. Training the model on only the most relevant subset of features, with the optimal hyperparameter value </br>

<b>Conclusion</b>: By choosing the feature with the highest f-score and the appropriate hyperparameter value (obtain using cross validation), we have a KNN Classifier that has 95% accuracy!

The models are implemented using scikit-learn in Python. Any feedback or suggestions would be highly appreciated!
