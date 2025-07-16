**🏦 Loan Approval Prediction Using Logistic Regression (R)**

This project applies a logistic regression model to predict whether a loan will be approved or rejected based on borrower and loan characteristics.

## 📊 View the Full Report

👉 [Click here to open the HTML report] (https://kimukev.github.io/loan-approval-logistic-regression/)



**📌 Project Overview**

This is an end-to-end machine learning project built in **R**, covering:

- Data cleaning and preparation  
- Handling class imbalance  
- Train/test split (80/20)
- Feature selection using **AIC (stepwise backward elimination)**
- Model training using **logistic regression**
- Model evaluation using:
  - Confusion matrix
  - ROC curve
  - AUC score
- Final output written in **R Quarto**  
- Deployed to GitHub for portfolio use
**🧰 Tools & Packages**
- `tidyverse`
- `caret`
- `pROC`
- `car` (for VIF)
- `knitr`, `rquarto`
**📁 File Structure**

| File              | Description                                 |
|-------------------|---------------------------------------------|
| `loan_model.qmd`  | Main R quarto file with full analysis       |
| `loan_model.html` | Rendered HTML report                        |
| `loan_data.csv`   | Cleaned dataset used for modeling           |
📊 Dataset

- **Source**: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/)
- **Target variable:** `loan_status` (`approved` or `rejected`)
- **Features include**: age, gender, income, loan intent, interest rate, credit score, etc.
  ✅ Model Performance

| Metric             | Score   |
|--------------------|---------|
| Accuracy           | 89.6%   |
| AUC (ROC)          | 0.954   |
| Sensitivity        | 0.73    |
| Specificity        | 0.94    |
| Balanced Accuracy  | 0.84    |

📈 ROC Curve

The model’s ROC curve demonstrates excellent separation between the two classes.  
An AUC of **0.954** indicates strong predictive ability and minimal misclassification.

🎯 Why Logistic Regression?

- Interpretable model for binary classification
- Easy to communicate results to non-technical stakeholders
- Performs well with limited features and a clean dataset

🔍 Future Improvements

- Try advanced models like Random Forest or XGBoost for comparison  
- Optimize classification threshold to balance precision/recall  
- Handle outliers and test for interaction terms

 🧑‍💻 Author

**Kevin Kimurgor**  
Data Analyst & Machine Learning Enthusiast  
📍 Nairobi, Kenya  
💼 [LinkedIn](https://www.linkedin.com/) | 
📧 kimurgorkev@gmail.com

---

> _This project is part of my machine learning portfolio. Feedback is welcome!_
