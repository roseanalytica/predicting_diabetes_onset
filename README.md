# Predicting Diabetes Onset: A Machine Learning Approach

## Overview
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases (uploaded at Kaggle: Pima Indians Diabetes Database). The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
  - Lower Mean Squared Error (MSE)
  - Lower Root Mean Squared Error (RMSE)
- Indicates Decision Tree captures training data with fewer errors.

**Testing Dataset Performance:**
- Both models perform closely on testing data.
- Linear Regression has slightly higher MAE, while Decision Tree has slightly higher MSE and RMSE.
- Both models demonstrate similar performance on unseen data.

**Model Fit to Data:**
- Decision Tree achieves a higher R-squared (R2) score on the training data, indicating a superior fit.
- Linear Regression has a slightly higher R2 score on the testing data, suggesting better generalization.

**Decision Making:**
- Based on these results, the Decision Tree model with a maximum depth of 3 seems to be the best model for use to predict diabetes onset.
