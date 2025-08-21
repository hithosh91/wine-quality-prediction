# Overview
The project is used to find the   quality of wine using supervised Machine Learning Algorithm(Support vector Classifier, Random Forest classifer)

# Main Objective
To classify wine quality into "bad" or "good" based on it attributes.
To compare the performance of Random Forest and Support Vector Machine (SVM) models.
To optimize the SVM model using GridSearchCV for hyperparameter tuning.
# features used wine data set
 Fixed acidity,
Volatile acidity,
Citric acid,
Residual sugar,
Chlorides,
Free sulfur dioxide,
Total sulfur dioxide,
Density,
pH,
Sulphates,
Alcohol,
Quality,

# Data workflow process
# 1.Data Preprocessing:

Loads the wine quality dataset using pandas.
Visualizes relationships between quality and features (fixed acidity, residual sugar) using seaborn bar plots.
Bins the quality column into "bad" (≤ 6.5) and "good" (> 6.5) categories.
Encodes the quality labels using LabelEncoder.
Splits the data into training (80%) and testing (20%) sets.
Scales the features using StandardScaler.

# 2.Model Training:

Trains a Random Forest Classifier with 200 estimators.
Trains a Support Vector Classifier (SVC) with default parameters.
Performs hyperparameter tuning for SVC using GridSearchCV with parameters

# output
# Random Forest Classifier:

Accuracy: ~0.85 
Cross-validation mean score: ~0.83 
Detailed classification report with precision, recall, and F1-score.


# Support Vector Classifier (Default):

Accuracy: ~0.80 
Classification report with performance metrics.


# Support Vector Classifier (GridSearchCV):

Accuracy: ~0.82 
Improved performance after hyperparameter tuning.

# dependencies
python
pandas
seaborn
matplotlib
scikit-learn
