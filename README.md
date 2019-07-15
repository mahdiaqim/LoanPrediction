# LoanPrediction
The data is the loan prediction dataset and is downloaded from Analytics Vidhya


## Problem Statement:
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.

The company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

## The Data
- Variable	Description
- Loan_ID	Unique Loan ID
- Gender	Male/ Female
- Married	Applicant married (Y/N)
- Dependents	Number of dependents
- Education	Applicant Education (Graduate/ Under Graduate)
- Self_Employed	Self employed (Y/N)
- ApplicantIncome	Applicant income
- CoapplicantIncome	Coapplicant income
- LoanAmount	Loan amount in thousands
- Loan_Amount_Term	Term of loan in months
- Credit_History	credit history meets guidelines
- Property_Area	Urban/ Semi Urban/ Rural
- Loan_Status	Loan approved (Y/N)

## Process
For this dataset I carried a complete analysis from EDA and data preprocessing and built different classification models (logistic regression, decision tree, random forrest, XGBoost, SVC and  KNN). Finally, I build the pipeline.

## Results
The results of the models accurancy are:

- Logistic Regression : 0.7847
- Decission Tree : 0.7569
- Radom Forest : 0.77778
- XGBoost : 0.79166
- Linear_SVC : 0.77778
- SVM_Classisifer : 0.77778
- KNeighborsClassifier : 0.7430
