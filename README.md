# Employee Attrition Prediction with Machine Learning

##  Project Overview
This project focuses on predicting employee attrition using **machine learning techniques**. By analyzing the IBM HR Analytics dataset, we aim to identify key factors influencing employee turnover and build a predictive model to assist HR departments in retention strategies.

##  Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Features:** Employee demographics, job role, experience, salary, etc.
- **Target Variable:** `Attrition` (Yes/No)

##  Tools & Technologies Used
- **Programming Language:** Python 
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Model:** Random Forest Classifier

##  Key Steps in the Project
1. **Exploratory Data Analysis (EDA)**
   - Data cleaning and preprocessing
   - Handling missing values & categorical encoding
   - Feature correlation analysis

2. **Feature Engineering**
   - Identifying key predictors of attrition
   - Removing low-variance features (e.g., `StandardHours`)

3. **Model Training & Evaluation**
   - Implemented **Random Forest Classifier**
   - Used **SMOTE** to handle class imbalance
   - Evaluated performance using:
     - Accuracy, Precision, Recall, F1-Score
     - Confusion Matrix, ROC-AUC Score

##  Results & Findings
- The model achieved **90% accuracy** in predicting employee attrition.
- Important factors influencing attrition include **Job Role, Monthly Income, Overtime, and Job Satisfaction**.
- HR teams can use these insights for **improving retention strategies**.

##  How to Run the Project
1. Install dependencies:
   ```bash
   pip install pandas numpy seaborn scikit-learn
   ```
2. Run the Jupyter Notebook or Colab file step by step.

## 📌 Author
👤 **Syed Uzair Ayan Ahmed**  
📧 Contact: uzairayan.2925@gmail.com  
💼 LinkedIn: linkedin.com/in/syeduzairayanahmed 
