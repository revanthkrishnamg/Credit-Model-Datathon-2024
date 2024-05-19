# Credit Scoring Model

## Overview
This project involves developing a credit scoring model for "Prêt à dépenser," a financial company that extends consumer credit to individuals, particularly those with minimal or no loan history. The primary goal of the model is to predict the probability of loan repayment and classify each application as either approved or refused credit.

## Datasets
The model utilizes various data sources including:
- **application_train.csv & application_test.csv**: Static data for all loan applications.
- **bureau.csv**: Data on client's previous credits from other financial institutions.
- **bureau_balance.csv**: Monthly balances of previous credits.
- **POS_CASH_balance.csv**: Monthly balance snapshots of previous POS and cash loans.
- **credit_card_balance.csv**: Monthly balance snapshots of previous credit card loans.
- **previous_application.csv**: Data on all previous applications for loans.
- **installments_payments.csv**: Repayment history for previously disbursed credits.

## Methodology
The approach to building the model involved several structured steps:

1. **Data Understanding and Import**
2. **Data Preprocessing and Aggregation**
3. **Feature Engineering**
4. **Imputation and Encoding**
5. **Feature Selection**
6. **Model Training and Evaluation**
7. **Model Selection and Prediction**
8. **Feature Importance Analysis**

Key machine learning techniques used include:
- Aggregation of numeric and categorical features.
- Advanced feature engineering to create insightful attributes.
- Implementation of LightGBM for feature selection.
- Training multiple models and selecting the best performer using metrics like F1 score and AUC.
- Handling class imbalance with SMOTE.
- Visualization of feature importance and ROC curves.

## Results
The project successfully developed a machine learning pipeline that predicts loan repayment probabilities with high accuracy. Feature importance analysis revealed that certain demographic and loan-related features significantly impact the likelihood of loan repayment.

## Usage
- The final model can be used to make predictions on new loan applications, helping the company decide whether to approve or refuse a credit application.
- The methodology and findings can also be leveraged to refine lending strategies and minimize credit risk.

## Tools and Libraries Used
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Matplotlib & Seaborn
- Imbalanced-learn

## How to Run
Ensure you have Python installed along with the necessary libraries. Clone the repository, navigate to the project directory, and run the Jupyter notebook to replicate the analysis or make new predictions.

## Conclusion
This project exemplifies the power of machine learning in financial decision-making and risk assessment. By carefully engineering features and selecting the right model, we can significantly enhance our ability to predict outcomes in the credit industry.
