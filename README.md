# 📉 Customer Churn Prediction using ML Models

This project predicts customer churn based on historical data using machine learning models like Logistic Regression, Decision Tree, and Neural Network. It addresses class imbalance using SMOTE and evaluates each model's performance using standard metrics.

---

## 📊 Dataset

- **Telco Customer Churn Dataset**
- Features include:
  - Tenure, Contract, Payment Method
  - Internet Service, Streaming Service
  - Tech Support, Monthly Charges, etc.

---

## 💡 Workflow

1. Data Preprocessing & Encoding
2. Handling Imbalanced Classes using **SMOTE**
3. Train-Test Split and Feature Scaling
4. Model Building:
   - Logistic Regression (gave the **best accuracy**)
   - Decision Tree Classifier
   - Neural Network (MLPClassifier with GridSearchCV)
5. Model Evaluation using:
   - Accuracy
   - ROC-AUC Score
   - Precision, Recall
   - F1 Score

---

## 📈 Performance Summary

Among all models tested, **Logistic Regression achieved the highest accuracy**, followed by Decision Tree and then Neural Network. Evaluation was done using test data after proper scaling and SMOTE balancing.

---

## 🧠 Tools & Libraries

- **Python** – Core programming language used for data analysis and machine learning.

- **pandas** – Used for reading the dataset, handling tabular data, cleaning and manipulating dataframes.

- **numpy** – Provides support for efficient numerical computations and array operations.

- **matplotlib** – Visualization library used to plot trends, distributions, and evaluation metrics.

- **seaborn** – Built on top of matplotlib; used for advanced visualizations like heatmaps and pairplots to explore relationships in data.

- **scikit-learn** – Core machine learning library used for:
  - Model building (Logistic Regression, Decision Tree, MLPClassifier)
  - Preprocessing (scaling, encoding)
  - Evaluation (accuracy, ROC-AUC, precision, recall, F1 score)

- **imbalanced-learn (SMOTE)** – Specialized library for handling imbalanced datasets; **SMOTE** (Synthetic Minority Over-sampling Technique) is used to balance class distribution before training.


---

## ✅ How to Run

```bash
git clone https://github.com/.../customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
```

## Models Performance showed by Bar Chart

<img width="1309" height="638" alt="Screenshot 2026-02-02 163625" src="https://github.com/user-attachments/assets/421c7cdc-3c55-451e-b15a-bc0b865b2642" />
