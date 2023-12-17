# LoanApproval-Classification

## Background
In the process of providing loans, banks are bound by a set of regulations to verify whether customers qualify for loan approval. Traditionally, banks examine the background and data of each customer individually. This manual approach is time-consuming and can lead to inefficiencies in the company's productivity. Therefore, data analysis is crucial to optimize the bank's strategy in determining loan approvals more efficiently.

The implementation of data analysis aims to enhance the bank's productivity in deciding whether a customer is eligible for a loan or not. The analysis is carried out using a classification measurement methodology focusing on the key factors influencing customers' loan applications. Once the classification is complete, the bank can easily decide whether to grant a loan or not.

## Objectives
The primary objectives of this research are as follows:

- Optimizing Loan Approval Process:
Implementing data analysis to streamline and optimize the bank's loan approval process.
- Efficiency in Decision-Making:
Increasing the efficiency of the bank's decision-making by predicting loan approval based on customer data.
- Classification Models:
Evaluating three classification models—Decision Tree, K-Nearest Neighbor (KNN), and Support Vector Machine (SVM)—to determine the most effective approach.

## Methodology
The research involves the following steps:

1. Data Understanding
    - Data Collection: Gathering relevant data related to customers applying for loans, including the seven key factors.
    - Data Exploration: Understanding the structure and nature of the collected data to identify potential challenges and opportunities.
2. Data Visualization (EDA)
    - Exploratory Data Analysis (EDA): Employing visualizations to uncover patterns, trends, and relationships within the dataset.
    - Correlation Analysis: Investigating the correlation between different factors to understand their impact on loan approval.
3. Data Preparation
    - Attribute Naming: Changing attribute names to enhance readability and clarity.
    - Outlier Elimination: Removing outliers using the z-score method to address significant differences in attribute values.
    - Encoding Categorical Variables: Converting categorical variables to numeric ones for effective model training.
    - Feature Selection: Removing unnecessary attributes that do not contribute significantly to the classification.
    - Missing Data Imputation: Filling in blank data using the decision tree regression method.
    - Data Splitting (Train and Test): Splitting the dataset into training and testing sets for model evaluation.
Model Training:
4. Model Comparison
    - Model Selection: Choosing Decision Tree, K-Nearest Neighbor (KNN), and Support Vector Machine (SVM) as classification models.
    - Model Training: Training each model on the pre-processed dataset.
    - Model Evaluation: Comparing the performance of each model using metrics such as accuracy, precision, recall, and F1 score.

## Conclusion
The study concludes that classification aims to predict the class of given data. The classification models attempt to predict class labels/categories for new data and draw conclusions from the provided input values for training. In this research, classification is conducted using three models: Decision Tree, KNN, and SVM. While each model has its advantages and disadvantages, KNN achieves the highest accuracy compared to the other two classification models. KNN classifies new data points based on the similarity measure with stored data points.

## Created With
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

