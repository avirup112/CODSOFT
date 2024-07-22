# Churn Prediction Project

This project aims to predict customer churn using machine learning models. The provided Jupyter Notebook demonstrates the process of data loading, preprocessing, feature engineering, model training, and evaluation.

## Steps:

1. **Data Loading:**
   - The dataset "Churn_Modelling.csv" is loaded using Pandas.

2. **Data Preprocessing:**
   - Irrelevant columns ('RowNumber', 'CustomerId', 'Surname') are dropped.
   - Missing values in 'CreditScore' are filled with the mean.
   - Duplicates are removed.
   - Categorical features ('Geography', 'Gender') are one-hot encoded.

3. **Feature Engineering:**
   - New features 'BalanceSalaryRatio' and 'TenureByAge' are created.

4. **Label Encoding:**
   - The target variable 'Exited' is encoded using LabelEncoder.
   - A new 'Churn' column is created, representing churn (1) or not (0).

5. **Data Splitting:**
   - The data is split into training (80%) and testing (20%) sets.

6. **Feature Scaling:**
   - Numerical features are scaled using StandardScaler.

7. **Model Training and Evaluation:**
   - Logistic Regression, Random Forest, and Gradient Boosting models are trained.
   - Models are evaluated using accuracy, precision, recall, and ROC AUC score.

8. **Hyperparameter Tuning (using GridSearchCV):**
   - GridSearchCV is applied to Random Forest and Gradient Boosting to find optimal hyperparameters.

9. **Best Model Selection:**
   - The best performing model is selected based on a chosen metric (e.g., accuracy).

## How to Run:

1. Upload "Churn_Modelling.csv" to the Colab environment.
2. Execute the Jupyter Notebook cells sequentially.

## Dependencies:

- pandas
- scikit-learn
- IPython

## Note:

- Ensure all necessary libraries are installed before running the notebook.
- Adjust hyperparameters and evaluation metrics based on specific requirements.
