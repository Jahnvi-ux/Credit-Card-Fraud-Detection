
# 💳 AI-Powered Credit Card Fraud Detection System

🔗 **Live Demo:** [Launch Application](https://credit-card-fraud-detection-st64.onrender.com/)

---

## 📌 Overview

This project presents a **machine learning-based web application** designed to detect fraudulent credit card transactions. The system analyzes transaction data and classifies it as **fraudulent or legitimate**, providing **real-time predictions** through an intuitive and interactive user interface.

---

## 🚨 Problem Statement

With the rapid growth of digital payments, **credit card fraud has become a critical challenge**. Detecting fraudulent transactions is difficult due to:

* Highly **imbalanced datasets** (fraud cases are rare)
* **Complex and hidden patterns** in transaction behavior

The objective of this project is to develop a **robust and accurate fraud detection system** that minimizes financial risks and enhances transaction security.

---

## ⚙️ Key Features

* 🔍 **Real-time fraud detection**
* ⚡ **Quick Test mode** for instant scenario-based predictions
* 🔬 **Advanced input simulation** for custom transaction testing
* 🎲 **Auto-fill sample data** for ease of use
* 📊 **Fraud probability visualization** for better interpretation

---

## 🧠 Technologies Used

* **Python**
* **Scikit-learn**
* **Pandas, NumPy**
* **Streamlit**
* **SMOTE** (for handling imbalanced datasets)

---

## 🤖 Machine Learning Approach

### 🔹 Data Preprocessing

* Feature scaling using **StandardScaler**
* Handling class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**

### 🔹 Model Selection

* **Random Forest Classifier**

  * Captures complex patterns effectively
  * Reduces overfitting through ensemble learning
  * Provides high accuracy and robustness

### 🔹 Evaluation Metrics

* **Accuracy**
* **Confusion Matrix**
* **Classification Report** (Precision, Recall, F1-score)

---

## 🖥️ Application Interface

### 🏠 Overview

Provides insights into credit card fraud and preventive measures

### ⚡ Quick Test

Allows users to test predefined **normal and fraudulent scenarios** instantly

### 🔬 Advanced Input

Enables users to simulate detailed transaction data and analyze fraud probability

---

## 📊 How It Works

1. User inputs transaction data
2. Data is preprocessed and scaled using a trained scaler
3. The model predicts whether the transaction is **fraudulent or legitimate**
4. A **probability score** is displayed for better decision-making

---

## 🚀 Future Enhancements

* Integration with **real-time banking systems**
* Implementation of **deep learning models**
* Incorporation of **Explainable AI (XAI)** for transparency
* Deployment as a **scalable API service**

---

## 📂 Project Structure

```
├── app.py
├── fraud_model.pkl
├── scaler.pkl
├── creditcard.ipynb
├── requirements.txt
├── screenshots/
├── demo/
├── confusion_matrix/
└── README.md
```

## 📚 References

* Kaggle Credit Card Fraud Dataset
* Scikit-learn Documentation

---

## 👨‍💻 Author

**Jahnvi Ranjan**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!


