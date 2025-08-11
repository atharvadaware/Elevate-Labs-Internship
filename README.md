## Heart Disease Prediction ML Project

This project aims to predict the presence of heart disease using machine learning models.

## Steps Involved:

1.  **Import Dependencies**: Import necessary libraries for data manipulation, visualization, and machine learning.
2.  **Load and Explore the Dataset**: Load the heart disease dataset into a pandas DataFrame and perform initial data exploration to understand its structure, dimensions, and check for missing values.
3.  **Separate Independent and Target Features**: Split the dataset into independent features (X) and the target variable (y).
4.  **Train-Test Split**: Divide the data into training and testing sets to evaluate the model's performance on unseen data.
5.  **Decision Tree Classifier Training & Evaluation**:
    *   Train a Decision Tree Classifier on the training data.
    *   Visualize the trained decision tree.
    *   Evaluate the model's performance on both the training and testing sets using accuracy scores.
6.  **Control Overfitting (Decision Tree Depth Tuning)**:
    *   Train a Decision Tree Classifier with a limited `max_depth` to mitigate overfitting.
    *   Evaluate the performance of the pruned Decision Tree on training and testing sets.
7.  **Random Forest Classifier Training & Evaluation**:
    *   Train a Random Forest Classifier on the training data.
    *   Evaluate the model's performance on both the training and testing sets using accuracy scores.
8.  **Control Overfitting (Random Forest Depth Tuning)**:
    *   Train a Random Forest Classifier with a limited `max_depth` to mitigate overfitting.
    *   Evaluate the performance of the pruned Random Forest on training and testing sets.
9.  **Interpret Feature Importances**: Visualize the feature importances from the Random Forest model to identify the most influential features in predicting heart disease.
10. **Cross-Validation for Robust Evaluation**:
    *   Perform cross-validation on both the pruned Decision Tree and the pruned Random Forest models to get a more robust estimate of their performance.
    *   Compare the cross-validation scores of the two models.
