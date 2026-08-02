# Loan Approval Analytics Dashboard

An end-to-end data analytics project analyzing loan application data to identify 
key factors influencing loan approval decisions.

## Project Overview
- Cleaned and preprocessed loan application data (missing values, duplicates, data types)
- Performed exploratory data analysis (EDA) and hypothesis testing (t-test)
- Built a Logistic Regression model to predict loan approval outcomes
- Developed an interactive Power BI dashboard for business insights

##  Key Insights
- Total Applications: 505 | Approval Rate: 68.51%
- Credit History is the strongest predictor of loan approval
- Applicant income alone does not significantly influence approval (p > 0.05)

##  Tools & Technologies
- **Python**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, SciPy
- **Power BI**: Interactive dashboard and visualizations
- **Dataset**: Loan Prediction dataset

## Repository Contents
- `loan_approval_analysis.ipynb` — Full analysis notebook (data cleaning, EDA, modeling)
- `dashboard_screenshot.png` — Power BI dashboard preview

## Dashboard Preview
<img width="1326" height="743" alt="image" src="https://github.com/user-attachments/assets/44ec7abd-5c18-4d56-84a3-8f422bd23ee0" />


## Model Performance
Evaluated using Accuracy, Precision, Recall, and F1-score with a confusion matrix.
<img width="575" height="462" alt="image" src="https://github.com/user-attachments/assets/8be11da0-8a06-4c2a-9cc6-c3a3a2273c7b" />

## Exploratory Data Analysis

### Loan Approval Distribution
<img width="666" height="512" alt="image" src="https://github.com/user-attachments/assets/cd21538f-8ee8-4b75-854c-1548744f3d1a" />

### Credit History vs Loan Status
Credit history shows a strong relationship with approval outcomes.
<img width="670" height="518" alt="image" src="https://github.com/user-attachments/assets/e44c9949-153f-49f3-8b73-b535c6c2a3c9" />

### Area vs Loan Status
<img width="693" height="510" alt="image" src="https://github.com/user-attachments/assets/80da78d0-1cff-40a4-ba56-cb6610f1eca2" />

### Applicant Income vs Loan Amount
<img width="723" height="517" alt="image" src="https://github.com/user-attachments/assets/d200f1d0-75b7-4ac0-b2f9-00e5e2594d1f" />

### Categorical Variables Overview
<img width="640" height="616" alt="image" src="https://github.com/user-attachments/assets/4b2a4b03-561f-4599-8085-068c50b3263e" />

