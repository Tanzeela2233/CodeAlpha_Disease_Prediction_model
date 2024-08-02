# MACHINE LEARNING TASK-04

## Introduction

This project aims to predict the likelihood of a disease based on medical data using machine learning classification algorithms. The dataset contains labeled medical records with various features such as age, sex, chest pain type, resting blood pressure, cholesterol level, etc. By training different classification models, we aim to identify patterns in the data that can accurately predict whether a patient has a disease.

## Classification Models Used:

I used the following classification models for this project:
1. **Logistic Regression**: A linear model for binary classification that estimates the probability that a given input belongs to a particular class.
2. **Decision Tree Classifier**: A non-linear model that splits the data into subsets based on feature values, forming a tree structure for decision making.
3. **Random Forest Classifier**: An ensemble method that combines multiple decision trees to improve prediction accuracy and control overfitting.

## Methodologies

1. **Data Preprocessing**:
   - Loaded the dataset and inspected the first few rows.
   - Checked for and handled any missing values.
   - Analyzed data types and basic statistics.
   - Visualized the distribution of the target variable.

2. **Feature Selection and Splitting Data**:
   - Identified the target variable (`target`).
   - Split the data into training and testing sets (80% training, 20% testing).

3. **Model Training**:
   - Initialized and trained three classification models: Logistic Regression, Decision Tree, and Random Forest.
   - Evaluated each model on the test set.

4. **Model Evaluation**:
   - Calculated accuracy, classification report, and confusion matrix for each model.
   - Visualized the results using confusion matrices and bar plots of prediction counts.

5. **Prediction Function**:
   - Implemented a function to make predictions on new patient data using the best-performing model.

## Conclusion

From the evaluation metrics, we can determine which model performs best for our dataset. The visualization of the predictions provides insights into the model's accuracy and potential areas of improvement. This project demonstrates the application of machine learning algorithms in the healthcare domain, offering a method to predict disease likelihood based on medical records.

## Visualization

To visualize the predictions, we:
- Created confusion matrices to show the number of correct and incorrect predictions for each class.
- Plotted bar charts to display the counts of predictions for each class (disease vs. no disease).



