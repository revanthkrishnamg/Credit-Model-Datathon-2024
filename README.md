# Credit Scoring Model - TBS Datathon 2024

## Overview
This project is about creating a model that helps a financial company called "Prêt à dépenser" decide whether to give someone a loan. The company focuses on people who haven't borrowed much money before. The main goal is to predict if a person will pay back their loan on time.

## Datasets

We use different sets of data to build our model, including:
- **application_train.csv & application_test.csv**: Information about all the loan applications.
- **bureau.csv**: Information about the borrower's past loans from other banks.
- **bureau_balance.csv**: Monthly details of past loans.
- **POS_CASH_balance.csv**: Monthly details about POS (point of sale) and cash loans.
- **credit_card_balance.csv**: Monthly details about credit card payments.
- **previous_application.csv**: Information on all past loan applications to the same company.
- **installments_payments.csv**: Details on how past loans were repaid.

## Steps in the Project
We built the model in several clear steps:

1. **Understanding and Loading Data**
2. **Preparing and Combining Data**
3. **Creating New Features**
4. **Filling Missing Values and Turning Categories into Numbers**
5. **Choosing the Most Important Features**
6. **Training and Picking the Best Model**
7. **Making Predictions with the Model**
8. **Analyzing Which Features are Most Important**

We used different techniques to make our model smart, such as:
- Combining information from different sources.
- Creating new features that help predict if a loan will be paid back.
- Using a technique called LightGBM to find out which features are most important.
- Comparing several models to find the best one.
- Balancing our data so that the model treats all scenarios fairly.
- Showing which features help make decisions about loans.

## Data Merging
### Initial Structure of the Data
![image1](https://github.com/revanthkrishnamg/Credit-Model-Datathon-2024/assets/149286080/5ab175cd-84d8-4ac9-a89e-22b6974daa55)

### Merging bureau_balance with bureau
![image2](https://github.com/revanthkrishnamg/Credit-Model-Datathon-2024/assets/149286080/2c2c80b7-9b0e-4a15-8d5c-35b8125b2970)

### Aggregation and Merging
![image_3](https://github.com/revanthkrishnamg/Credit-Model-Datathon-2024/assets/149286080/b6546529-7223-4617-a56b-83f4bd708da3)

### Final Merged Data Structure
![image_4](https://github.com/revanthkrishnamg/Credit-Model-Datathon-2024/assets/149286080/25daaba3-e35a-4738-b481-3768c4b5ae16)

## Results
We built a model that can predict quite accurately whether someone will pay back their loan. We also found out which details about a person or their loan matter most in deciding if they will pay back on time.

## Tools and Libraries
To do this project, we used:
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Matplotlib & Seaborn
- Imbalanced-learn

## Conclusion
This project shows how machine learning can help make important decisions like giving out loans. By carefully choosing and preparing features, and selecting the right model, we can greatly improve how well we predict outcomes in lending.

## Team Members
Diana 
Vivek 
Chayanika
Aman
Cathal
Revanth


