# Credit Risk Modeling (Loan Default Prediction)

## Project Overview
This project predicts the probability of loan default using historical borrower data.  
It simulates a real-world credit risk modeling scenario that banks and financial institutions face when evaluating loan applications.

## Business Context
Banks need to identify risky borrowers before approving loans.  
By predicting defaults, they can reduce financial losses and improve **risk management**.

## Technologies & Libraries
- Python (Pandas, NumPy, Scikit-learn)
- Logistic Regression
- Random Forest
- StandardScaler for feature scaling

##  Dataset
Dataset: [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)  
- Rows: ~30K borrower records  
- Key Features: `loan_amnt`, `annual_inc`, `funded_amnt`, etc.  
- Target: `loan_status` (0 = Paid, 1 = Default)

## Steps Implemented
1. Data cleaning & feature engineering  
   - Created `DebtToIncome` and `LoanToValue` ratios  
2. Train-test split  
3. Scaled features (for Logistic Regression)  
4. Trained **Logistic Regression** (interpretable model)  
5. Trained **Random Forest** (higher accuracy, non-linear patterns)  
6. Evaluated with Accuracy, Confusion Matrix, Classification Report  

## 📊 Results
- Logistic Regression Accuracy: ~85%  
- Random Forest Accuracy: ~90%  
- Random Forest captured complex borrower patterns better.  
