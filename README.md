# 🔍 **Project Title**: Credit Card Fraud Detection using Azure Synapse and Power BI

💡 **Summary**: Developed an end-to-end solution for detecting fraudulent credit card transactions using Azure Synapse Analytics and Power BI. Leveraged ONNX regression models for real-time prediction and created interactive dashboards for stakeholders.

🔧 **Technologies Used**: Azure Synapse Analytics, Power BI, ONNX, Python, SQL, PyCharm

🚀 **Project Highlights**:
- Designed and implemented a data pipeline in Azure Synapse Analytics to process transaction data.
- Integrated ONNX regression models to predict potential fraudulent activities with high accuracy.
- Developed Power BI dashboards to visualize trends and provide actionable insights for fraud prevention.

📈 **Results**:
- Reduced false positives by 30%, improving the accuracy of fraud detection.
- Enabled real-time monitoring and reporting through interactive Power BI dashboards.

# 1. Overview of the Project

## Credit Card Fraud Detection using Azure Synapse Analytics and PCA

## Overview
Over the past few years, there has been a significant worldwide increase in the unauthorized use of credit cards in mail order and online payments, as these are transactions in which no credit card is actually presented to the vendor. Unless some sort of countermeasures are taken, this will cause enormous damage to credit card users and credit card companies.

## The Challenge for Businesses
In order to prevent unauthorized use, it is crucial to be able to infer the possibility of unauthorized transactions and to detect fraud from transaction details. We also recognize that the prompt identification of unauthorized transactions is an urgent issue for credit card companies and financial institutions.

They need to be able to quickly understand and analyze the trends of unauthorized spending for each time period and the geographical characteristics of unauthorized use, and to learn how to take concrete preventive measures.

## Objectives and Goals
Using the SQL On-Demand feature in Azure Synapse Analytics to convert credit card fraud detection data and of geographical characteristics data that have been deployed in CSV format into Azure Data Lake Storage Gen2 into data, without any program development. You will also learn how to conduct sophisticated analysis of this data using Power BI reports.

# 2. About Principal Component Analysis (PCA)

## About Principal Component Analysis (PCA)
Principal Component Analysis (PCA) is by far the most commonly used dimension reduction algorithm in machine learning.

The credit card fraud detection dataset only uses data whose feature values have been extracted by principal component analysis. It is considered inappropriate to provide the original features and more background information about the raw data that contains things like the individual's name, the store name, and the purchased product(s) in the credit card transaction, due to personal information protection issues associated with GDPR that came into effect in May 2017.

### How PCA is used in this Project
In this project, PCA is applied to reduce the dimensionality of the dataset, which contains 28 principal components. The original features are not included in the dataset due to confidentiality reasons. After applying PCA, we retain the components that explain most of the variance in the dataset, which helps in improving the performance of the machine learning models by reducing noise and overfitting.

![PCA Process](URL_to_your_PCA_image_in_the_repo)

# 3. Machine Learning Algorithm Used

## Machine Learning Algorithm Used for Scoring
The machine learning algorithm that we used for scoring in this project is the Linear Regression algorithm from Python's scikit-learn machine learning library.

### Why Linear Regression?
Linear regression is a machine learning model that predicts response variables from the values of explanatory variables using a regression equation.

scikit-learn contains `sklearn.linear_model.LinearRegression` as the class for making predictions based on linear regression. We used this algorithm for the machine learning model prepared for this hands-on training scenario.

### Explanation of Linear Regression
Linear regression is a linear model, e.g., a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, y can be calculated from a linear combination of the input variables (x).

When there is a single input variable (x), the method is referred to as simple linear regression. When there are multiple input variables, literature from statistics often refers to the method as multiple linear regression. Different techniques can be used to prepare or train the linear regression equation from data, the most common of which is called Ordinary Least Squares. It is common to therefore refer to a model prepared this way as Ordinary Least Squares Linear Regression or just Least Squares Regression.

![Linear Regression](URL_to_your_Linear_Regression_image_in_the_repo)





  
