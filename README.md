# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit card fraud has become one of the most significant challenges in the digital payment ecosystem. With millions of transactions occurring every day, detecting fraudulent activities quickly and accurately is crucial for financial institutions.

This project focuses on building a Machine Learning-based Fraud Detection System capable of identifying suspicious credit card transactions. By leveraging data preprocessing techniques, class imbalance handling methods, and predictive modeling, the system aims to distinguish legitimate transactions from fraudulent ones with high accuracy and reliability.

The project demonstrates the complete Machine Learning workflow, including data exploration, preprocessing, model training, evaluation, and performance analysis.

---

## 🚀 Key Features

✅ Comprehensive Exploratory Data Analysis (EDA)

✅ Data Cleaning and Preprocessing

✅ Feature Scaling and Transformation

✅ Handling Highly Imbalanced Data

✅ Machine Learning Model Training

✅ Performance Evaluation using Multiple Metrics

✅ Fraud Detection Insights and Visualization

✅ End-to-End Machine Learning Pipeline

---

## 📂 Project Structure

```text
Credit_Card_Fraud_Detector/
│
├── credit_card_fraud.ipynb      # Main Jupyter Notebook
├── creditcard.csv               # Dataset (Local Only)
├── README.md                    # Project Documentation
└── requirements.txt             # Required Libraries (Optional)
```

---

## 📊 Dataset Information

The dataset contains anonymized credit card transactions made by European cardholders.

### Features

| Feature Type | Description                                   |
| ------------ | --------------------------------------------- |
| V1 - V28     | PCA-transformed confidential features         |
| Time         | Seconds elapsed between transactions          |
| Amount       | Transaction amount                            |
| Class        | Target Variable (0 = Genuine, 1 = Fraudulent) |

### Important Note

The dataset is highly imbalanced:

* Genuine Transactions ➜ ~99.8%
* Fraudulent Transactions ➜ ~0.2%

This makes fraud detection a challenging real-world classification problem.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Prathibha856/Credit_Card_fraud_detector.git
cd Credit_Card_fraud_detector
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv .venv
```

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

### 4️⃣ Launch Notebook

```bash
jupyter notebook credit_card_fraud.ipynb
```

---

## 🔍 Project Workflow

### 1. Data Collection

* Load transaction dataset
* Inspect structure and missing values

### 2. Exploratory Data Analysis

* Fraud vs Non-Fraud distribution
* Transaction amount analysis
* Correlation analysis
* Outlier detection

### 3. Data Preprocessing

* Feature scaling
* Data splitting
* Handling class imbalance

### 4. Model Building

* Train Machine Learning model
* Generate predictions
* Evaluate performance

### 5. Performance Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## 🤖 Machine Learning Techniques Used

### Logistic Regression

A strong baseline model that performs surprisingly well for fraud detection tasks.

### Class Weight Balancing

Assigns higher importance to fraudulent transactions during training.

### Resampling Techniques

* Random Undersampling
* Random Oversampling
* SMOTE (Synthetic Minority Oversampling Technique)

These techniques help address the severe class imbalance problem.

---

## 📈 Evaluation Metrics

For fraud detection, **Accuracy alone is not sufficient** because the dataset is highly imbalanced.

Instead, we focus on:

### Precision

Measures how many detected frauds were actually frauds.

### Recall

Measures how many actual frauds were successfully identified.

### F1-Score

Balances Precision and Recall.

### ROC-AUC

Evaluates overall classification performance.

💡 In fraud detection, **Recall is often the most important metric** because missing a fraudulent transaction can be more costly than flagging a legitimate one.

---

## 🧠 Quick Learning Summary

### Why Fraud Detection is Difficult?

* Fraud cases are extremely rare.
* Models can achieve 99% accuracy by predicting everything as legitimate.
* Detecting the minority class is the real challenge.

### Important Interview Insight

If a model gives:

```text
Accuracy = 99.8%
Recall = 0%
```

The model is useless because it failed to detect any fraud transactions.

Always evaluate Precision, Recall, and F1 Score along with Accuracy.

---

## 💡 Tips & Tricks for Better Fraud Detection Models

### ✅ Use Stratified Train-Test Split

Maintains the fraud-to-legitimate ratio in both training and testing datasets.

### ✅ Scale Transaction Amount

Models often perform better after feature normalization.

### ✅ Focus on Recall

Missing a fraud transaction is usually more expensive than a false alarm.

### ✅ Handle Class Imbalance

Use:

* SMOTE
* Class Weights
* Oversampling
* Undersampling

### ✅ Analyze Confusion Matrix

Provides deeper insights into model performance.

### ✅ Experiment with Advanced Models

Try:

* Random Forest
* XGBoost
* LightGBM
* CatBoost
* Neural Networks

These models often outperform basic classifiers on fraud detection datasets.

---

## 🔮 Future Improvements

* Random Forest Implementation
* XGBoost Model
* LightGBM Integration
* Hyperparameter Tuning
* Model Deployment with Flask/FastAPI
* Real-Time Fraud Detection API
* Streamlit Web Application
* Docker Containerization
* CI/CD Pipeline Integration

---

## 🎯 Real-World Applications

* Banking Systems
* Credit Card Companies
* Digital Payment Platforms
* E-Commerce Fraud Monitoring
* Insurance Claim Fraud Detection
* Financial Risk Assessment

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.

---

## 👨‍💻 Author

**Prathibha D**

Machine Learning Enthusiast | Data Science Learner | Future AI Engineer

📌 GitHub: https://github.com/Prathibha856
