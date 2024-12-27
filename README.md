# 💷💳 LoanTap - ML Case Study 💳💷  
## Logistic Regression Model for Loan Approval Prediction  

![image](https://github.com/user-attachments/assets/c83f9707-4f3b-4089-892f-d06768518c28)


---

## 📝 Case Report  
🔗 [Access the Python File](https://github.com/ssgalactic/LoanTap-ML-Case_Study/blob/main/Business_Case_LoanTap_Logistic_Regression_Sabyasachi.ipynb)  
🔗 [Download the Case Study PDF](https://github.com/ssgalactic/LoanTap-ML-Case_Study/blob/main/Business_Case_LoanTap_Logistic_Regression_Sabyasachi_PDF_11zon.pdf)  

---

## 💳 Introduction  
LoanTap is a leading fintech company in India, providing innovative and flexible loan products. This case study focuses on building a logistic regression model to analyze personal loan data, identify borrower patterns, and predict creditworthiness.  

By leveraging machine learning, LoanTap enhances loan disbursal efficiency while minimizing risks.  

---

## 🔹 Task Description  
As a data scientist at LoanTap, you are responsible for:  
- Analyzing the loan dataset to derive key insights.  
- Developing and evaluating a logistic regression model.  
- Providing actionable recommendations to refine the underwriting process.  

---

## 📊 Dataset Overview  
### 🔍 Column Profiling  
| Feature                   | Description  |  
|---------------------------|---------------------------------------------------------|  
| **loan_amnt**              | Loan amount applied by the borrower.                    |  
| **term**                   | Loan term (36 or 60 months).                            |  
| **int_rate**               | Interest rate on the loan.                              |  
| **installment**            | Monthly payment by the borrower.                        |  
| **grade**                  | Loan grade assigned by LoanTap.                         |  
| **emp_length**             | Employment length (0 to 10+ years).                     |  
| **annual_inc**             | Borrower's annual income.                               |  
| **verification_status**    | Income verification status.                             |  
| **loan_status**            | Target variable - loan status (approved/rejected).      |  
| **dti**                    | Debt-to-income ratio.                                   |  
| **revol_bal**              | Total revolving balance.                                |  
| **open_acc**               | Number of open credit lines.                            |  
| **mort_acc**               | Number of mortgage accounts.                            |  

---

## 📈 Model Development  
- **Model Type**: Logistic Regression  
- **Accuracy**: 85%  
- **AUC-ROC Score**: 0.89  
- **Key Finding**: Borrowers with a credit score above **750** had a **30% higher approval rate**.  
- **Feature Importance**: Debt-to-Income ratio (DTI), annual income, and credit history significantly impacted the predictions.  

---

## 🛠️ Tech Stack  
- **Modeling**: Logistic Regression  
- **Evaluation Metrics**: Accuracy, AUC-ROC Curve,Precision, Recall
- **Programming**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Optimization**: GridSearchCV, ROC-AUC  

---

## 📊 Visualization  
- Confusion Matrix  
- ROC Curve  
- Feature Importance Bar Chart  

---

## 📌 Conclusion  
The logistic regression model successfully optimized LoanTap’s personal loan underwriting process, providing insights into borrower behavior and potential risks.  
