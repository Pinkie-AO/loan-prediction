# Loan Default Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict whether a loan application will be approved based on applicant characteristics such as income, credit score, employment status, and existing financial obligations.

The goal is to build a machine learning model that can assist financial institutions in making informed lending decisions and reducing default risk.

---

## 📊 Dataset
The dataset contains 1000 observations with the following features:

- Age  
- Gender  
- Marital Status  
- Annual Income  
- Loan Amount  
- Credit Score  
- Number of Dependents  
- Existing Loans Count  
- Employment Status  
- Loan Approved (Target Variable)  

---

## ⚙️ Data Preprocessing
The following steps were performed:

- Removed irrelevant column (`applicant_id`)
- Converted categorical variables into numerical format using one-hot encoding
- Split data into training (80%) and testing (20%) sets

---

## 🤖 Models Used

### 1. Logistic Regression
- Baseline model
- Easy to interpret

### 2. Random Forest
- Ensemble model using multiple decision trees
- Captures complex relationships in data

---

## 📈 Model Performance

| Model | Accuracy |
|------|--------|
| Logistic Regression | 87.5% |
| Random Forest | 98% |

---

## 🔍 Evaluation Metrics (Random Forest)

- Accuracy: 98%  
- Precision: 0.97 (Approved loans)  
- Recall: 1.00 (Approved loans)  

Confusion Matrix:
[[ 51 4]
[ 0 145]]

---

## 💡 Key Insights

- **Credit score** is the most important factor in loan approval decisions  
- **Number of dependents** significantly affects financial risk  
- **Existing loans** increase the likelihood of rejection  
- **Employment status** plays a key role, especially unemployment  
- **Income is important but less influential than credit behavior**

---

## ⚠️ Limitations

- The model may be slightly overfitted due to high accuracy  
- Further validation with external datasets is recommended  

---

## 🚀 Conclusion

The Random Forest model significantly outperformed Logistic Regression, achieving high accuracy and capturing complex patterns in the data.

This project demonstrates how machine learning can be applied to real-world financial decision-making.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Jupyter Notebook (VS Code)

---

## 📌 Future Improvements

- Hyperparameter tuning  
- Cross-validation  
- Deployment using Streamlit  
- Use of larger and more diverse datasets  

---

## 👩‍💻 Author

**Pinkie Akinyi Odipo**

MSc Applied Statistics | Data Enthusiast  