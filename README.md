
# Home Loan Approval Prediction

Home Loan Approval Prediction system is designed to predict the likelihood of a customer's loan approval using machine learning techniques. In financial sectors, determining loan eligibility has traditionally been a complex, manual, and often subjective process which can have human biases. 


## Dataset

This dataset contains information on 1033 loan applications that were either accepted or rejected. The dataset includes several key features for each application, as detailed below.

### Key Features

1. **Loan_id**: A unique identifier assigned to each customer.
2. **Gender**: Gender of the applicant, either Male or Female.
3. **Married**: Marital status of the applicant, with values Yes or No.
4. **Dependents**: Indicates if the applicant has any dependents.
5. **Education**: Indicates whether the applicant is a Graduate or not.
6. **Self_Employed**: Indicates if the applicant is self-employed, with values Yes or No.
7. **ApplicantIncome**: Income of the applicant.
8. **CoapplicantIncome**: Income of the co-applicant.
9. **LoanAmount**: Loan amount requested (in thousands).
10. **Loan_Amount_Term**: Loan term duration (in months).
11. **Credit_History**: Applicant’s credit history, indicating their past repayment behavior.
12. **Property_Area**: Area where the property is located, either Rural, Urban, or Semi-urban.


## Method

Our methodology is that we have first done the data preprocessing and then spilitted the data as mentioned below and then we have trained the following machine learning Models
- Logistic Regression
- Random Forest Classifier

### Dataset Splitting

The dataset is split into two subsets to evaluate model performance and generalization ability:
- **Training Set**: 70% of the data (approximately 723 entries) used to train the model.
- **Testing Set**: 30% of the data (approximately 310 entries) used to test the model on unseen data.
## Results

The accuracy for the machine learning models used are:
- Logistic Regression 80.13%
- Random Forest Classifier 76.01%

Below are the Confusion Matrices for the respective machine learning models:

Logistic Regression

![App Screenshot](https://github.com/harrshyadav24/Home-Loan-Approval-Prediction/blob/main/Logistic%20Regression.png)

Random Forest Classifier

![App Screenshot](https://github.com/harrshyadav24/Home-Loan-Approval-Prediction/blob/main/Random%20Forest%20Classifier.png)
