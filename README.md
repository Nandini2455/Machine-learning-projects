This project predicts wine quality based on various features using a RandomForestClassifier model. The model is trained on a wine dataset and utilizes GridSearchCV for hyperparameter tuning.

Project Overview
Wine quality prediction is a classification problem where the aim is to classify wine samples into quality categories based on chemical properties. This project trains a RandomForestClassifier model and optimizes it using GridSearchCV, evaluating performance on a test dataset with accuracy and other classification metrics.

Dataset
The dataset contains features like:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality (target variable)
Results
Best Parameters: Displayed based on the GridSearchCV optimization.
Accuracy: The accuracy score of the model on the test dataset.
Confusion Matrix and Classification Report: Detailed classification metrics.
Usage
To run the code:

Load the dataset.
Split the data into training and test sets.
Run the model training and evaluation code.
