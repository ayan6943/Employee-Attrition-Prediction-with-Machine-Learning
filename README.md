# 🧠 Employee Attrition Prediction with Machine Learning (Random Forest & XGBoost)

This project focuses on predicting employee attrition using two machine learning approaches — **Random Forest** and **XGBoost** — trained on the IBM HR Analytics dataset. It aims to help HR departments proactively identify at-risk employees and develop effective retention strategies.

By incorporating **SHAP explainability** with XGBoost, the project not only achieves high accuracy but also provides transparent insights into why employees may leave.

---

## 📊 Dataset

- **Source**: [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Features**: Employee demographics, job role, income, overtime, satisfaction, etc.
- **Target**: `Attrition` (Yes/No)

---

## 🧰 Tools & Technologies

| Component       | Tools Used |
|------------------|-------------|
| Language         | Python |
| Libraries        | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, SHAP |
| Models           | Random Forest, XGBoost |
| Explainability   | SHAP (for XGBoost) |
| Imbalance Handling | SMOTE |

---

## 🧪 Project Workflow

1. **EDA & Data Cleaning**
   - Visualized attrition patterns by role, overtime, satisfaction
   - Removed irrelevant/constant columns like `StandardHours`
   - Handled missing values and categorical variables

2. **Feature Engineering**
   - Identified key predictors
   - Encoded categorical variables and scaled numerical ones

3. **Modeling**
   - Trained both **Random Forest** and **XGBoost**
   - Addressed class imbalance using **SMOTE**
   - Evaluated using Accuracy, F1-Score, Precision, Recall, ROC-AUC

4. **Explainability (XGBoost only)**
   - Used **SHAP** to visualize feature importance and explain individual predictions

---

## 📈 Model Performance Comparison

| Metric        | Random Forest | XGBoost + SHAP |
|---------------|---------------|----------------|
| Accuracy      | 90%           | **92%**        |
| Precision     | 0.88 / 0.93   | **0.91 / 0.92** |
| Recall        | 0.93 / 0.87   | **0.93 / 0.91** |
| F1-Score      | 0.90          | **0.92**       |
| ROC-AUC       | 0.90          | **0.971** ✅    |

> 🚀 **XGBoost** outperformed Random Forest, especially in ROC-AUC and class balance, making it more reliable for real-world deployment.

---

## 🔍 SHAP Explainability (XGBoost)

- **SHAP Summary Plot**: Visualizes global feature importance
- Most influential features:
  - `OverTime`, `MonthlyIncome`, `JobSatisfaction`, `JobRole`

---

## 📄 License

This project is licensed under the MIT License.
