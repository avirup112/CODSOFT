# Fraud Detection Project

This project aims to detect fraudulent transactions using machine learning models.

## Steps:

1. **Data Loading:** Load the dataset 'fraudTest.csv' (ensure it's available in the environment).
2. **Data Preprocessing:**
   - Handle missing values using SimpleImputer.
   - Convert 'trans_date_trans_time' to a numeric representation (Unix timestamp).
   - Handle non-numeric columns (e.g., dropping them).
   - Scale numerical features using StandardScaler.
3. **Model Training:**
   - Train a Logistic Regression model.
   - Train a Decision Tree Classifier model.
4. **Model Saving:**
   - Save trained models using joblib (fraud_detection_model.pkl, fraud_detection_dt_model.pkl).
5. **Model Loading:**
   - Load saved models for prediction.
6. **Prediction:**
   - Predict on new data using the loaded models.
7. **Evaluation:**
   - Evaluate model performance using metrics like accuracy, confusion matrix, and classification report.

## Usage:

1. Ensure necessary libraries are installed (e.g., pandas, scikit-learn, joblib).
2. Run the provided code in a Google Colab environment or a similar setup.
3. Replace placeholders in the example prediction sections with actual data.

## Note:

- This README provides a basic overview. Refer to the code comments for more details.
- Adjust the code and parameters as needed for your specific dataset and requirements.
