# Loan Applicant Credit Risk Analysis
# Project Overview
This project focuses on classifying loan applicants into different risk segments using K-Nearest Neighbors (KNN). The dataset contains various details about the applicants, such as Age, Total Work Experience, Number of Years in City, and Cost to Request Ratio. The objective is to preprocess the data to handle any irregularities and noise and to use a KNN classifier to achieve accurate predictions.
# Problem Statement
Classifying loan applicant risk is crucial for analyzing financial data and improving lending strategies. This project aims to develop a KNN classifier that accurately predicts the risk segmentation based on various features.
# Data Cleaning
Data cleaning is essential to ensure the dataset's quality and reliability. The raw dataset may contain missing values, inconsistencies, and outliers. The following steps were performed:
- **Handling Missing Values:** Missing values were imputed using strategies such as mean, median, or mode, or by removing records with excessive missing data.
- **Outlier Detection and Removal:** Outliers in continuous variables were identified and removed to prevent distortion in the model.
- **Standardization:** Standardized categorical variables and fixed formatting inconsistencies to ensure uniformity across the dataset.
# Exploratory Data Analysis (EDA)
EDA was conducted to understand the data better and to uncover patterns and relationships. The analysis included:
- **Distribution Analysis:** Examined the distribution of key features such as Age, Total Work Experience, and Cibil Score to understand their spread and central tendencies.
- **Scatter Plot: Age vs. Total Work Experience:** Visualized the relationship between Age and Total Work Experience using a scatter plot.
- **Box Plot for Age:** Used a box plot to identify outliers and the spread of Age.
- **Box Plot for Cibil Score:** Visualized the distribution and outliers of Cibil Score.
- **Feature Relationships:** Explored the relationship between categorical features (e.g., Number of Years in City, Cost to Request Ratio) and the target variable using various visualizations.
  # Feature Engineering
  - **One-Hot Encoding:** Applied one-hot encoding to categorical variables like Number of Years in City and Cost to Request Ratio to convert them into numerical format.
  - **Feature Scaling:** Scaled numerical features to ensure they contributed equally to the model.
  - **Feature Selection:** Based on EDA insights, irrelevant or redundant features were dropped to improve model performance.
  # Model Building
  The dataset was used to build and evaluate the KNN classifier for predicting loan applicant risk segmentation:
  - **Create Target and Feature Data:** The target variable is Total Bounces Past 12 Months and the feature variables are the rest of the dataset.
  - **Split Data:** The dataset is split into training and testing sets.
  - **Build KNN Classifier:** Train the KNN classifier using the training data.
  # Model Evaluation
  The model was evaluated based on its training and test scores and the accuracy of predictions for different K values.
  # Results
  The results of the KNN classifier evaluation are as follows:

 - **Training Score:** The model achieved a training score of 67%.

 - **Test Score:** The model achieved a test score of 64%.

 - **Accuracy Score:** The model achieved an accuracy score of 64%.

 - **K-Value Analysis:** The training and testing scores for different K values helped identify the best K value for optimal performance.
   # Conclusion
   This project demonstrates the process of developing a predictive model for loan applicant risk segmentation using K-Nearest Neighbors. The KNN classifier provided reasonable accuracy, and tuning the K value was crucial to optimize performance.



