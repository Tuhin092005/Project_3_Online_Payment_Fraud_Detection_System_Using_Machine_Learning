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
| Logistic Regression | **80.83%** |
| Decision Tree | **91.00%** |
| Random Forest | **96.67%** ✅ |

### 🏆 Best Performing Model

**Random Forest Classifier**

Accuracy: **96.67%**

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

# 📷 Output

### Prediction Example

```
Prediction: 0

Transaction Status : Legitimate Transaction
```

or

```
Prediction: 1

Transaction Status : Fraudulent Transaction
```

---

# 📁 Project Structure

```
Online_Payment_Fraud_Detection_System/
│
├── Online_Payment_Fraud_Detection_System.ipynb
├── Online_Payment_Fraud_Detection_System.py
├── Dataset/
│   ├── Online_Payment_Fraud_Dataset.csv
├── images/
│   ├── Confusion_Matrix.png
│   ├── Feature_Importance.png
│   └── Model_Accuracy_Comparison.png
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Tuhin092005/Project_3_Online_Payment_Fraud_Detection_System_Using_Machine_Learning.git
```

Move into the project folder

```bash
cd Project_3_Online_Payment_Fraud_Detection_System_Using_Machine_Learning
```

Install the required libraries

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
