# Customer Churn Prediction using Machine Learning

## Overview

This project focuses on predicting customer churn using machine learning techniques applied to the IBM Telco Customer Churn dataset, available on Kaggle. Customer churn is a critical business metric that refers to the phenomenon where customers discontinue their services with a company. By identifying potential churners early, businesses can take proactive measures to retain customers and optimize strategies.

### Dataset Information

- **Source**: IBM Telco Customer Churn dataset from Kaggle
- **Content**: Customer information, services utilized, and churn-related details.
- **Features**: Demographics, service usage details, contract specifics.
- **Target Variable**: Churn (binary: 0 or 1)

### Preprocessing Steps

1. **Handling Missing Values**: Converted 'Total Charges' to numeric, filled NaN values based on 'Tenure Months' and 'Monthly Charges.'
2. **Data Cleaning**: Checked and handled duplicates.
3. **Feature Engineering**: Created new features like 'Tenure Years' and 'Monthly to Total Charges Ratio.'
4. **Categorical Data Handling**: Utilized techniques such as one-hot encoding, label encoding, and value replacements.

## Exploratory Data Analysis (EDA)

- Explored distribution of churn across geographic, demographic, and service-related categories.
- Visualized correlations among numerical columns using a heatmap.

## Model Development and Evaluation

This project evaluated multiple machine learning models to predict customer churn:

- **Logistic Regression**: Accuracy - 96.38%, Precision - 95.00%, Recall - 88.00%
- **GaussianNB**: Accuracy - 97.59%, Precision - 92.00%, Recall - 100.00%
- **Random Forest Classifier**: Accuracy - 99.72% (ROC AUC: 99.48%), Precision - 99.00%, Recall - 100.00%
- **Support Vector Machine (SVM)**: Accuracy - 99.93%, Precision - 100.00%, Recall - 100.00%

### Result Analysis

- Highlighted superior performance of Random Forest and SVM models in accuracy, precision, and recall.
- Conducted feature importance analysis to identify key predictors contributing to churn.

## Deployment Plan

### Process Description

1. **Export Machine Learning Items from Notebook**: Extracted relevant ML artifacts (models, preprocessing steps).
2. **Import Machine Learning Items into the App Script**: Integrated ML items into application script.
3. **Build an Interface**: Created user-friendly interface for data input and model prediction.
4. **Process Inputs**: Developed function to handle user inputs and connect with ML model.
5. **Predict and Display**: Implemented processing steps, fed inputs to model, and displayed predictions on the interface.

## Conclusion

### Achievements

- Developed and evaluated robust machine learning models for customer churn prediction.
- Demonstrated high accuracy and reliability in predicting customer behavior patterns.

### Future Steps

- Plan for continuous monitoring and updates to keep the model relevant.
- Explore enhancements by adding new features or refining existing ones to improve prediction capabilities.
