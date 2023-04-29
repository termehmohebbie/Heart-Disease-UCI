# Heart Disease UCI
The Heart Disease UCI dataset contains data on heart disease patients from the Cleveland Clinic Foundation. This dataset has 303 rows and 14 columns, which are mostly self-explanatory. The goal of this project is to develop a machine learning model that can predict the presence of heart disease based on these features.

# Data Preparation:
The dataset contained no missing values, so there was no need to do any imputation. The categorical variables were one-hot encoded using the get_dummies function. The continuous variables were then scaled using the StandardScaler function. The target variable, target, was binary, with 1 indicating the presence of heart disease and 0 indicating the absence of heart disease.

# Exploratory Data Analysis:
The dataset contained 165 positive and 138 negative cases of heart disease. The correlation matrix showed that the features with the highest correlation to the target variable were cp, thalach, slope, and oldpeak. The features with the lowest correlation to the target variable were fbs and chol.

# Modeling:
Several models were tested including Logistic Regression, Random Forest, Decision Tree and XGBoost. The best performing model was Logistic Regression with an accuracy of 61.67%%, followed by Random Forest with an accuracy of 60%. The accuracy of the other models was as follows: XGBoost (60%), and Decision Tree (55%).

The Random Forest model had an AUC score of 0.95, indicating good performance in distinguishing between positive and negative cases. The feature importance plot showed that the most important features in the model were cp, thalach, and oldpeak.

# Conclusion:
In this project, we analyzed the Heart Disease UCI dataset and built a machine learning model to predict the presence of heart disease. The best performing model was Logistic Regression, with an accuracy of 61.67%. The most important features in the model were cp, thalach, and oldpeak. Overall, this project demonstrates the utility of machine learning in predicting heart disease and highlights the importance of feature selection in building accurate models.
