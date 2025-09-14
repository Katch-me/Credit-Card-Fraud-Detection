# Credit-Card-Fraud-Detection-Using-Machine-Learning

## ABSTRACT
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machine learning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.  

**Keywords:** Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree  

---

## Overview
With the increase of people using credit cards in their daily lives, credit card companies should take special care of the security and safety of the customers. According to *Credit card statistics 2021*, the number of people using credit cards worldwide was 2.8 billion in 2019; also, 70% of those users own a single card. Reports of credit card fraud in the U.S. rose by 44.7% in 2020.  

There are two common types of credit card fraud:  
1. **New account fraud** – when an identity thief opens a new account under your name.  
2. **Account takeover fraud** – when an identity thief uses your existing account, usually by stealing card details.  

Reports of these fraudulent behaviors increased significantly in 2020, motivating the need to resolve the issue analytically by using machine learning methods to detect fraudulent transactions.  

---

## Project Goals
- Detect fraudulent credit card transactions to protect customers from unauthorized charges.  
- Apply multiple ML algorithms for detection and compare their performance.  
- Provide evaluation with graphs and metrics (Accuracy, Precision, Recall, F1-Score).  
- Explore previous literature and techniques to strengthen fraud detection.  

---

## Data Source
The dataset was retrieved from Kaggle:  
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

- Transactions made in **2013** by European credit card users over **2 days**.  
- **284,808 rows** with **31 attributes**.  
- 28 attributes transformed using **PCA** for confidentiality.  
- Features include `Time`, `Amount`, and `Class` (binary: 1 = Fraud, 0 = Not Fraud).  

---

## Algorithms Used
1. K-Nearest Neighbor (KNN)  
2. Logistic Regression (LR)  
3. Support Vector Machine (SVM)  
4. Decision Tree (DT)  

---

## Installation & Requirements

**Requirements:**
- Python 3.8+
- Jupyter Notebook / Google Colab
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn  

Install dependencies:
```bash
pip install -r requirements.txt
