# Customer Repurchase Prediction using Federated Learning

## Overview

Customer retention is a critical challenge in e-commerce. This project develops a predictive analytics solution to identify customers who are likely to make repeat purchases while preserving data privacy through Federated Learning.

The study simulates distributed customer datasets across multiple business districts and evaluates different Federated Learning approaches under Non-IID and imbalanced data conditions.

---

## Business Problem

E-commerce businesses need to identify customers with a high probability of making repeat purchases in order to improve customer retention, optimize marketing campaigns, and increase customer lifetime value.

Traditional centralized machine learning requires aggregating all customer data into a single location, which may raise privacy concerns. This project explores Federated Learning as an alternative approach that enables collaborative model training without sharing raw customer data.

---

## Dataset

The project uses customer transaction data collected from multiple sales districts.

### Prediction Target

* **1** = Customer makes a repeat purchase
* **0** = Customer does not make a repeat purchase

### Data Challenges

* Non-IID (Non-Independent and Identically Distributed) data across districts
* Imbalanced customer classes
* Distributed data environment

---

## Methodology

### Data Preparation

* Data cleaning and preprocessing
* Feature engineering
* Label generation for repurchase prediction
* Client-based data partitioning by sales district

### Federated Learning Framework

Implemented and compared:

* Logistic Regression
* Random Forest
* Multi-Layer Perceptron (MLP)
* FedAvg
* FedProx

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

---

## Results

### Best Performing Model: FedProx + MLP

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 93.18% |
| Precision | 80.16% |
| Recall    | 88.06% |
| F1-Score  | 83.92% |

### Key Findings

* Federated Learning achieved strong predictive performance while preserving data privacy.
* FedProx improved model stability under Non-IID data conditions.
* The proposed approach outperformed several baseline models in customer repurchase prediction.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Federated Learning
* Google Colab
* Power BI

---

## Repository Structure

```text
├── notebooks/
│   └── customer-repurchase-prediction-federated-learning.ipynb
│
├── images/
│   └── dashboard.png
│
└──  README.md
```

---

## Key Skills Demonstrated

* Data Analytics
* Exploratory Data Analysis (EDA)
* Data Cleaning & Transformation
* Feature Engineering
* Predictive Analytics
* Machine Learning
* Federated Learning
* Model Evaluation
* Data Visualization
* Business Problem Solving

---

## Author

**Tran Hoang Thanh Thu**

Data Analyst | Business Intelligence | Data Analytics
* GitHub: https://github.com/ththanhthu2307-eng
