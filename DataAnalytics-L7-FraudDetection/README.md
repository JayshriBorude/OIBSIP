# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project builds a machine learning pipeline to detect fraudulent credit card transactions using classification algorithms. Since fraudulent transactions are extremely rare compared to legitimate ones, the project addresses class imbalance and evaluates models using metrics beyond simple accuracy.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship – Level 2 Task 3**.

---

## 🎯 Objective

- Detect fraudulent credit card transactions.
- Handle class imbalance using `class_weight="balanced"` (or SMOTE if available).
- Compare multiple machine learning models.
- Evaluate models using Precision, Recall, F1-Score, and ROC-AUC.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

Credit Card Fraud Detection Dataset

Features include:
- Time
- Amount
- V1–V28 (PCA-transformed features)
- Class (0 = Normal, 1 = Fraud)

---

## 🔄 Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Class Imbalance Analysis
4. Feature Scaling
5. Train-Test Split (Stratified)
6. Class Imbalance Handling
7. Logistic Regression
8. Random Forest
9. Model Evaluation
10. ROC Curve
11. Feature Importance
12. Model Comparison
13. Conclusion

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## 🤖 Models Used

- Logistic Regression
- Random Forest Classifier

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| Logistic Regression | 99.914% | 82.67% | 63.27% | 71.68% |
| Random Forest | 99.961% | 94.19% | 82.65% | 88.04% |

**Best Model:** Random Forest Classifier

---

## 📊 Visualizations

- Class Distribution
- Transaction Amount Distribution
- Transaction Time Distribution
- Confusion Matrix
- ROC Curve
- Feature Importance
- Model Comparison

---

## 🚀 Real-World Applications

- Credit Card Fraud Detection
- Online Banking Security
- Payment Gateway Monitoring
- Insurance Fraud Detection
- Financial Risk Management

---

## 📁 Folder Structure

```
DataAnalytics-L7-FraudDetection
│
├── Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
├── requirements.txt
└── images
```

---

## 👩‍💻 Author

**Jayshri Borude**

Oasis Infobyte Data Analytics Intern