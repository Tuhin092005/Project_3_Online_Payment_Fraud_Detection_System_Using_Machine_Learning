# 💳 Online Payment Fraud Detection System

> An intelligent Machine Learning project that detects fraudulent online payment transactions using multiple classification algorithms.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

# 📖 Project Overview

Online payment fraud has become one of the biggest challenges in digital transactions. This project uses Machine Learning algorithms to classify whether a transaction is **Legitimate** or **Fraudulent** based on transaction details.

The system performs data preprocessing, feature encoding, feature scaling, model training, prediction, and performance evaluation using three popular Machine Learning algorithms.

---

# 🎯 Objectives

- Detect fraudulent online payment transactions.
- Compare multiple Machine Learning algorithms.
- Improve fraud detection accuracy.
- Reduce financial losses caused by fraudulent transactions.

---

# 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📂 Dataset Features

The dataset contains important transaction details such as:

- **step** – Represents the time step (hour) of the transaction.
- **type** – Type of transaction (e.g., CASH_IN, CASH_OUT, DEBIT, PAYMENT, TRANSFER).
- **amount** – Amount of money involved in the transaction.
- **nameOrig** – Unique identifier of the sender's account.
- **oldbalanceOrg** – Sender's account balance before the transaction.
- **newbalanceOrig** – Sender's account balance after the transaction.
- **nameDest** – Unique identifier of the receiver's account.
- **oldbalanceDest** – Receiver's account balance before the transaction.
- **newbalanceDest** – Receiver's account balance after the transaction.
- **isFraud** – Indicates whether the transaction is fraudulent (**1**) or legitimate (**0**).
- **isFlaggedFraud** – Indicates whether the transaction was flagged as suspicious by the system.

### 🎯 Target Variable

- **isFraud**
  - **0 → Legitimate Transaction**
  - **1 → Fraudulent Transaction**

---

# ⚙️ Machine Learning Algorithms Used

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

# 📊 Model Performance

| Machine Learning Model | Accuracy |
|------------------------|---------:|
| Logistic Regression | **78.33%** |
| Decision Tree | **93.67%** |
| Random Forest | **96.50%** ✅ |

### 🏆 Best Performing Model

**Random Forest Classifier**

Accuracy: **96.50%**

---

# 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Handling Missing Values
   │
   ▼
Encoding Categorical Data
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
```

---

# 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 💳 Sample Predictions

The model predicts whether an online payment transaction is **Fraudulent** or **Legitimate** using two different transaction examples.

### 🧪 Example Prediction 1 (Fraudulent Transaction)

**Input**

```text
Step               : 600
Transaction Type   : TRANSFER
Amount             : 950000
Old Balance Origin : 950000
New Balance Origin : 0
Old Balance Dest   : 0
New Balance Dest   : 950000
Flagged Fraud      : 0
```

**Expected Output**

```text
Prediction : 1

Transaction Status : Fraudulent Transaction
```

> A high-value transfer that empties the sender's account is predicted as a **Fraudulent Transaction**.

---

### 🧪 Example Prediction 2 (Legitimate Transaction)

**Input**

```text
Step               : 250
Transaction Type   : PAYMENT
Amount             : 4500.75
Old Balance Origin : 15000.00
New Balance Origin : 10500.25
Old Balance Dest   : 5000.00
New Balance Dest   : 9500.75
Flagged Fraud      : 0
```

**Expected Output**

```text
Prediction : 0

Transaction Status : Legitimate Transaction
```

> A normal payment transaction with a reasonable amount and valid balance update is predicted as a **Legitimate Transaction**.

---

# 📁 Project Structure

```
Project_3_Online_Payment_Fraud_Detection_System_Using_Machine_Learning/
│
├── Online_Payment_Fraud_Detection_System.ipynb
├── Online_Payment_Fraud_Detection_System.py
├── Dataset/
│   ├── Online_Payment_Fraud_Dataset.csv
├── images/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_accuracy_comparison.png
├── best_model.pkl
├── feature_names.pkl 
├── label_encoders.pkl
├── scaler.pkl 
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Tuhin092005/Project_3_Online_Payment_Fraud_Detection_System_Using_Machine_Learning.git
```

### Navigate to the project

```bash
cd Project_3_Online_Payment_Fraud_Detection_System_Using_Machine_Learning
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

### Using Python

```bash
python Online_Payment_Fraud_Detection_System.py
```

### Using Google Colab

Open

```text
Online_Payment_Fraud_Detection_System.ipynb
```

Upload:

- Online_Payment_Fraud_Dataset.csv

Run all cells.

---

# 📌 Future Improvements

- Deep Learning based fraud detection
- Real-time fraud monitoring
- Web Application using Flask or Streamlit
- API Integration
- Explainable AI (XAI)

---

# 👨‍💻 Author

**Tuhin Maji**

B.Tech CSE (Artificial Intelligence & Machine Learning)

Meghnad Saha Institute of Technology (MSIT)

---

# ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub.

It motivates future development and improvements.

---

## 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational purposes.
