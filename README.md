# Objective: 
Developed a predictive model using Tesla stock price data (2010-2017) to analyze and forecast stock movements.

# Approach:

Data Preprocessing: Cleaned and prepared the dataset for analysis.
Feature Engineering: Created new features to enhance model performance.
Exploratory Data Analysis: Conducted to gain insights into the data.

# Models Implemented:

Logistic Regression
Support Vector Machine (SVM)
XGBoost

# Methodology:

Data Splitting: Divided the data into training and validation sets.
Performance Evaluation: Used ROC-AUC metric to assess model accuracy.

# Results:

XGBoost: Achieved the highest training accuracy but showed signs of overfitting.
Logistic Regression: Provided a more balanced performance between training and validation accuracy.

# Conclusion: 
XGBoost performed well on training data but struggled with unseen data, indicating overfitting. Logistic Regression, while more stable, did not significantly outperform random guessing. The project highlighted the complexities of stock market prediction and suggested the need for more advanced models or additional data to improve accuracy.
