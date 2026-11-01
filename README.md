# Project_Loan-Approval-Dataset-ML
# Loan Approval Prediction (Machine Learning)

A university machine learning project that predicts whether a loan applicant
is eligible for loan approval, based on personal, financial, and credit data.

## Team Project
Developed by a team of 4 students as part of a university machine learning course.
My contribution: Data Preprocessing (data cleaning and validation).

## Dataset
Loan Prediction Problem Dataset (Kaggle)
- 614 records, 11 features after dropping Loan_ID
- Target: Loan_Status (1 = Approved, 0 = Rejected)

## Data Preprocessing
1. Missing value check: found in Gender, Married, Dependents,
   Self_Employed, LoanAmount, Loan_Amount_Term, and Credit_History
   (Credit_History had the most, 8.14%).
2. Handling missing values:
   - Categorical columns filled with the mode
   - Numerical columns filled with the median
   - Result: 0 missing values remaining
3. Label encoding of categorical columns into numeric values
4. Defining X and y and dropping Loan_ID
5. Train/Test split: 80% train (491 rows) / 20% test (123 rows)
6. Feature scaling using StandardScaler

## Models
| Metric | Logistic Regression | Random Forest |
|—|—|—|
| Accuracy | 0.86 | 0.83 |
| Rejected Recall | 0.58 | 0.63 |
| Approved Recall | 0.99 | 0.92 |
| Macro F1 | 0.81 | 0.79 |

## Results
- Logistic Regression achieved the best overall accuracy (86.18%).
- Random Forest was better at catching rejected loans (higher recall
  for the Rejected class).
- Both models predict approved loans better than rejected ones, because the
  dataset has more approved examples than rejected ones.

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Kaggle Notebooks

## How to Run
1. Download the dataset from Kaggle (Loan Prediction Problem Dataset).
2. Open the .ipynb notebook in Jupyter or Kaggle.
3. Run all cells.
