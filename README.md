# Credit-Card-Fraud-Detection-Using-Machine-Learning

## ABSTRACT
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machine learning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.  

**Keywords:** Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree  

---

## Overview

Credit card fraud continues to escalate globally, particularly as online and digital payments grow more common. According to the **Federal Trade Commission (FTC)**, consumers reported more than **US $12.5 billion** in losses due to fraud in 2024 — a ~25% increase from 2023. ([ftc.gov](https://www.ftc.gov/news-events/news/press-releases/2025/03/new-ftc-data-show-big-jump-reported-losses-fraud-125-billion-2024?utm_source=chatgpt.com))  

Identity theft, especially involving credit card fraud (both opening new accounts and misuse of existing ones), remains among the most reported fraud types, with **~449,000 credit card identity theft cases** in the U.S. in 2024. ([lifelock.norton.com](https://lifelock.norton.com/learn/credit-finance/credit-card-fraud-statistics?srsltid=AfmBOoqZNz8YJaWsb4BTMSrPLol-rfWwlNPGHe9rGngekGY7uzB6eiHI&utm_source=chatgpt.com))  

There are multiple types of credit card fraud:  
1. **New account fraud** – when someone opens a credit account using stolen or synthetic identities.  
2. **Account takeover fraud** – when someone illegally uses someone else’s existing account/card details.  
3. **Card-not-present fraud (CNP)** – fraud where the physical card is not required (online, phone, etc.).  

These trends emphasize the urgency of detecting fraudulent transactions early, using machine learning. That is the motivation behind this project: to build models that help distinguish between fraudulent vs. legitimate transactions using real transactional data, evaluate multiple algorithms, and thereby mitigate risk for users and institutions.

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

--
## Acknowledgment

This project draws inspiration from the open-source work of **Md. Shakil Hossain**.  
It has been further modified, refined, and extended by **Khushi Vasava** to enhance its functionality and presentation.  

Special thanks to the open-source community and Kaggle for providing valuable resources and datasets that made this project possible.
