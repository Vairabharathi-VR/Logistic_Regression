# Logistic Regression for Classification

## Introduction

Logistic Regression is a widely used statistical method in Machine Learning for binary classification problems. It is particularly effective when the dependent variable is binary, indicating two possible outcomes (e.g., yes/no, spam/not spam). Logistic Regression models the probability that an instance belongs to a particular category.

### Significance of Logistic Regression

Logistic Regression is commonly employed in scenarios where the outcome is categorical and binary. Some common applications include:

- **Spam Detection:** Identifying whether an email is spam or not.
- **Medical Diagnostics:** Predicting whether a patient has a particular medical condition or not.
- **Credit Scoring:** Determining if a customer is likely to default on a loan.

## Project Report

### Methodology

#### 1. Data Preprocessing

- Imported necessary packages for data analysis.
- Loaded the dataset using a comma separator.
- Converted object data types to integer using label encoding.
- Checked for null values in the dataset.

#### 2. Logistic Regression Model

- Defined the logistic regression model with 'y' as the dependent variable and the remaining columns as independent variables.
- Split the data into training and testing sets.
- Trained the logistic regression model and assessed its accuracy.

#### 3. Scaling Techniques

- Applied scaling techniques to improve the model accuracy.
- Explored the impact of different scaling methods on model performance.

#### 4. Hyperparameter Tuning

- Conducted a loop to find the random state yielding the maximum accuracy.
- Iterated over 1000 random state values and identified the best-performing model.

### Conclusion

In conclusion, the logistic regression model demonstrated promising results for the classification task. The initial accuracy of 88.94% was improved to 89.14% through the application of scaling techniques. The exploration of different random state values further revealed the optimal configuration for achieving the highest accuracy.

This project highlights the versatility of Logistic Regression in handling binary classification problems and showcases the importance of data preprocessing and iterative optimization in enhancing model performance.

