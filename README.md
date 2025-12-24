<img width="1536" height="1024" alt="ChatGPT Image Dec 24, 2025, 08_40_50 PM" src="https://github.com/user-attachments/assets/72b18ec6-e8d5-45f8-8eef-fade122d819d" />
![Uploading ChatGPT Image Dec 24, 2025, 08_40_50 PM.png…]()
"""
<p align="center">
  <img src="https://img.shields.io/badge/Bank%20Marketing%20Term%20Deposit%20Prediction-ML%20Project-blue?style=for-the-badge&logo=python&logoColor=white" />
</p>

<p align="center">
  <b>
    Machine Learning • EDA • Logistic Regression • SVM • Random Forest • Banking Analytics
  </b>
</p>

# 🏦 BANK MARKETING TERM DEPOSIT PREDICTION PROJECT

---

## 🎯 Project Objectives
- Perform **Exploratory Data Analysis (EDA)** to understand data patterns and relationships
- Identify and analyze **outliers** and their impact on customer subscription
- Handle **class imbalance** effectively
- Build and evaluate multiple **machine learning models**
- Compare models using appropriate evaluation metrics
- Recommend the **best-performing model** for deployment

---

## 📊 Dataset Information
- **Dataset Name:** bank-additional-full.csv
- **Domain:** Banking & Finance
- **Target Variable:** `y`
  - `1` → Customer subscribed to term deposit
  - `0` → Customer did not subscribe
- **Total Features:** 20 input features + 1 target
- **Data Type:**
  - Categorical features (job, marital status, education, etc.)
  - Numerical features (age, duration, campaign, economic indicators)

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
- **Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

## 🔍 Methodology
1. Data Loading and Understanding
2. Exploratory Data Analysis (EDA)
3. Handling Missing and `unknown` Values
4. Outlier Detection using IQR Method
5. Feature Engineering and Encoding
6. Train–Test Split with Stratification
7. Handling Class Imbalance (Over-Sampling)
8. Model Building:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
9. Model Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
10. Model Comparison and Final Selection

---

## 📈 Model Performance Summary

| Model | Accuracy | Recall (Yes) | Precision (Yes) | F1-Score (Yes) |
|-----|--------|--------------|----------------|---------------|
| Logistic Regression | 90.81% | 84.96% | 42% | 0.56 |
| SVM | 83.60% | 83.11% | 40% | 0.54 |
| Random Forest | 90.81% | 63.85% | 60% | 0.62 |

---

## 🏆 Final Conclusion
- Logistic Regression and SVM achieved **high recall**, identifying most potential subscribers but produced many false positives.
- Random Forest provided the **best balance between precision and recall**, resulting in the **highest F1-score (0.62)**.
- Random Forest is selected as the **final and production-ready model** due to better overall reliability and reduced unnecessary marketing efforts.

---

## 💡 Business Impact
- Improved customer targeting
- Reduced marketing costs
- Higher campaign efficiency
- Data-driven decision-making for bank marketing teams

---


## 🚀 Future Scope
- Apply advanced ensemble methods (XGBoost, LightGBM)
- Perform hyperparameter tuning using GridSearchCV
- Deploy the model using Flask or FastAPI
- Integrate real-time prediction system

---

## 🙏 Acknowledgement
I would like to thank my mentor and instructors for their guidance and support throughout this project.

---

## ✨ Author
**Aniket Jain**  
Aspiring Data Scientist / Data Engineer
"""
