# Loan Approval Prediction (Machine Learning)

A university machine learning project that predicts whether a loan applicant is eligible for loan approval, based on personal, financial, and credit data.

## Team Project

Developed by a team of 4 students as part of a university machine learning course.
My contribution: **Data Preprocessing** (data cleaning and validation).

## Dataset

Loan Prediction Problem Dataset (Kaggle)

- 614 records, 11 features after droppingligible for- Target:proval Predicti(1 = Approved, 0 = Rejected)

## Data Preprocessing

1.sity machine learning projfound in Gender, Married, Dependents, Self_Employed, LoanAmount, Loan_Amount_Term, and Credit_History (Credit_History had the most, 8.14%).
2.an approval, based on personal   - Categorical columns filled with thening)

A u   - Numerical columns filled with thearning)

A u   - Result: 0 missing values remaining
3.ng)

A university maof categorical columns into numeric values
4.

A university machineand droppingval Predict5.Loan Approval Predictio80% train (491 rows) / 20% test (123 rows)
6.

A university machinusingn Approval Predict
## Models

-al Prediction (Logistic Regression 0.86 | Random Forest 0.83
-A university machine lLogistic Regression 0.58 | Random Forest 0.63
-A university machine lLogistic Regression 0.99 | Random Forest 0.92
-A university maLogistic Regression 0.81 | Random Forest 0.79

## Results

-machine learning project achieved the best overall accuracy (86.18%).
-
A university machiwas better at catching rejected loans (higher recall for the Rejected class).
- Both models predict approved loans better than rejected ones, because the dataset has more approved examples than rejected ones.

## Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Kaggle Notebooks

## How to Run

1. Download the dataset from Kaggle (Loan Prediction Problem Dataset).
2. Open theet

Loan Pnotebook in Jupyter or Kaggle.
3. Run all cells.
