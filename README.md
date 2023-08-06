# Breast_cancer_prediction_model

## Overview
- Built a model that accepts cell nucleus values features of a breast cancer tumor as input and predicts if the cancer is Benign or Malignant.
- Model is trained on a dataset of 570 Breast Cancer Images from the Kaggle Wisconsin UCI Breast Cancer dataset.
- Data was trained on 5 different models. K-fold cross-validation was performed to validate for overfitting and a final trained Support Vector Machine (SVM) model was used to build the predictor.

## Data Cleaning
- Column with Null Values was removed.
- Got the count of malignant vs benign tumor cells.
- Performed encoding to to represent categorical variables as numerical values to use it in the ML model.

## EDA
- Various analysis was made related to the dataset and the models. Below are a few highlights.
![image](https://github.com/roshanmurkar/Breast_cancer_prediction_model/assets/85471797/52bf7d95-d31b-4cc0-b621-8decfcdd73ee)
![image](https://github.com/roshanmurkar/Breast_cancer_prediction_model/assets/85471797/68d36f99-f81d-4fbc-a8f5-6d7fc9b56e52)

## Model Building

StandardScaler method was used to remove the mean and scale each feature/variable to unit variance. The data was split into train and test sets with a test size of 20%.
Five different models were tried and evaluated based on their metrics:
- Logistic Regression
- K-Nearest Neighbor
- Decision Tree Classifier
- Random Forest Method
- Support Vector Machines

## Model performance

The SVM model outperformed the other approaches on the test and validation sets.

- Random Forest : Accuracy = 94.73%
- Decision Tree : Accuracy = 93.85%
- Logistic Regression: Accuracy = 96.49%
- K-NN: Accuracy = 95.61%
- SVM: Accuracy = 98.24%


