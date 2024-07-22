# Spam Detection Project

This project aims to build a machine learning model that can accurately classify SMS messages as spam or ham (legitimate). 

## Dataset

The project utilizes the "spam.csv" dataset, which contains a collection of SMS messages labeled as either spam or ham. The dataset was preprocessed to handle missing values, duplicates, and perform necessary cleaning steps.

## Exploratory Data Analysis (EDA)

EDA was performed to gain insights into the dataset. This included visualizing the distribution of spam and ham messages, analyzing the number of characters, words, and sentences in each message, and exploring correlations between features.

## Data Preprocessing

The following preprocessing steps were applied to the text data:

- Lowercasing
- Tokenization
- Removal of special characters
- Removal of stop words and punctuation
- Stemming

## Model Building

Various machine learning models were trained and evaluated, including:

- Gaussian Naive Bayes
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression
- Random Forest
- AdaBoost
- Bagging Classifier
- Extra Trees Classifier
- Gradient Boosting
- XGBoost

## Model Evaluation

The models were evaluated based on accuracy and precision scores. The performance of different models was compared to identify the most suitable algorithm for spam detection.

## Model Improvement

Techniques such as adjusting the `max_features` parameter of TF-IDF vectorization and applying scaling were explored to potentially improve model performance.

## Ensemble Methods

Ensemble methods, including Voting Classifier and Stacking, were employed to combine the predictions of multiple models and potentially achieve better results.

## Conclusion

The project successfully demonstrated the application of machine learning for spam detection. The best-performing models achieved high accuracy and precision scores, indicating their effectiveness in classifying SMS messages.
