# Customer Churn Prediction using Random Forest

## Overview
This project focuses on predicting customer churn using a machine learning model trained on a dataset of approximately 7000 customers. The best-performing model, a Random Forest classifier with cross-validation accuracy of 0.84, was selected for deployment.

## Dataset
- The dataset consists of customer-related features influencing churn behavior.
- It contains both numerical and categorical attributes.

## Steps Involved
### 1. Data Loading and Understanding
- Imported the dataset and explored its structure.
- Identified key features and target variables.

### 2. Exploratory Data Analysis (EDA)
- **Numerical Data Analysis:** Examined the distribution of numerical variables.
- **Categorical Data Analysis:** Visualized categorical distributions.
- **Heatmap Analysis:** Checked for correlations among features.

### 3. Data Preprocessing
- Handled missing values (if any).
- Encoded categorical variables.
- Scaled numerical features.
- Split data into training and testing sets.

### 4. Model Training and Evaluation
Three machine learning techniques were used:
1. **Decision Tree**
2. **Random Forest** (Best performer with accuracy of 0.84)
3. **XGBoost**

After evaluation, Random Forest was chosen as the final model due to its superior performance.

### 5. Model Deployment and Prediction
- The trained Random Forest model was loaded.
- Predictions were made on random customer data.
- Model performance was assessed using evaluation metrics.

## Usage
1. Load the dataset.
2. Run the preprocessing and training scripts.
3. Use the saved Random Forest model for prediction.
4. Provide customer data to predict churn likelihood.

## Dependencies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Conclusion
This project successfully predicts customer churn with a high accuracy using the Random Forest algorithm. Future improvements could include hyperparameter tuning and feature engineering for even better results.

