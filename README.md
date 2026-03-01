# DevelopersHub Corporation — Data Science & Analytics Internship Tasks

> 📊 Open each `.ipynb` file above to see full code, visualizations, and results.

This repository contains all 5 completed tasks for the Data Science & Analytics Internship at DevelopersHub Corporation.  
Each task is a fully self-contained Jupyter Notebook covering data loading, EDA, modeling, and evaluation.

---

## 📁 Repository Structure

```
📦 internship-tasks/
 ┣ 📓 Task_1_Iris_EDA.ipynb
 ┣ 📓 Task_2_Credit_Risk_Prediction.ipynb
 ┣ 📓 Task_3_Customer_Churn_Prediction.ipynb
 ┣ 📓 Task_4_Insurance_Claim_Prediction.ipynb
 ┣ 📓 Task_5_Personal_Loan_Acceptance.ipynb
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
```

---

## ✅ Task Summaries

### Task 1 — Exploring and Visualizing the Iris Dataset
| | |
|---|---|
| **Objective** | Understand how to read, summarize, and visualize a dataset |
| **Dataset** | Iris Dataset (via `sklearn.datasets`) |
| **Approach** | Loaded with pandas → inspected shape/dtypes → created scatter plots, histograms, box plots, heatmap, and pairplot using matplotlib and seaborn |
| **Key Insight** | Petal length & petal width are the most discriminative features; Setosa is clearly linearly separable |

---

### Task 2 — Credit Risk Prediction
| | |
|---|---|
| **Objective** | Predict whether a loan applicant is likely to default |
| **Dataset** | Loan Prediction Dataset (Kaggle structure) |
| **Approach** | Missing value imputation → Label Encoding → Logistic Regression & Decision Tree classifier |
| **Evaluation** | Accuracy, Confusion Matrix, Classification Report |
| **Key Insight** | Credit history is the single strongest predictor of loan approval |

---

### Task 3 — Customer Churn Prediction (Bank Customers)
| | |
|---|---|
| **Objective** | Identify customers likely to leave the bank |
| **Dataset** | Churn Modelling Dataset (10,000 bank customers) |
| **Approach** | Label Encoding + One-Hot Encoding → StandardScaler → Random Forest classifier |
| **Evaluation** | Accuracy, ROC-AUC, Confusion Matrix, Feature Importance |
| **Key Insight** | Age is the top churn predictor; German customers churn at a higher rate |

---

### Task 4 — Predicting Insurance Claim Amounts
| | |
|---|---|
| **Objective** | Estimate medical insurance charges from personal data |
| **Dataset** | Medical Cost Personal Dataset (Kaggle structure) |
| **Approach** | Linear Regression baseline + Gradient Boosting for improved accuracy |
| **Evaluation** | MAE, RMSE, R² score |
| **Key Insight** | Smoking status drives charges most heavily; BMI and age also significant |

---

### Task 5 — Personal Loan Acceptance Prediction
| | |
|---|---|
| **Objective** | Predict which customers will accept a personal loan offer |
| **Dataset** | Bank Marketing Dataset (UCI ML Repository structure) |
| **Approach** | EDA on demographics → Label Encoding → Logistic Regression & Decision Tree |
| **Evaluation** | Accuracy, ROC-AUC, Confusion Matrix, Business Segment Analysis |
| **Key Insight** | Call duration & previous campaign success are the strongest acceptance signals; target management/retired + tertiary-educated customers |

---

## 🛠️ Setup & Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/developershub-ds-internship.git
cd developershub-ds-internship

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

Then open any `.ipynb` file and run all cells (`Kernel → Restart & Run All`).

---

## 📦 Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
jupyter>=1.0.0
```

---

## 📊 Skills Demonstrated

| Skill | Tasks |
|---|---|
| Data Loading & Inspection | All |
| Data Cleaning & Missing Value Handling | 2, 3, 4, 5 |
| Exploratory Data Analysis (EDA) | All |
| Data Visualization (matplotlib & seaborn) | All |
| Categorical Encoding (Label / One-Hot) | 2, 3, 5 |
| Classification Modeling | 2, 3, 5 |
| Regression Modeling | 4 |
| Model Evaluation (Accuracy, MAE, RMSE, ROC-AUC) | All |
| Feature Importance Analysis | 3, 5 |
| Business Insight Extraction | 2, 3, 5 |

---

## 👤 Author

**Maryam Adeeba**  
Data Science & Analytics Intern — DevelopersHub Corporation  
Due Date: 2nd March, 2026

---

## 📄 License

This project is for educational purposes as part of the DevelopersHub internship program.
