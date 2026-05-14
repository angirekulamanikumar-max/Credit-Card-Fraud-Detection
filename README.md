# Credit Card Fraud Detection using Machine Learning

## Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. With the rapid growth of online banking and digital payments, fraud detection has become a critical problem in the financial industry.

The goal of this project is to build a robust and reliable model that can accurately identify fraudulent transactions while minimizing false positives.

---

## Abstract

The usage of credit/debit cards and online banking has increased significantly in recent years. However, this growth has also led to a rise in fraudulent activities. Many users unknowingly share sensitive information such as card details and OTPs with fraudsters, leading to financial losses.

Detecting fraud is challenging because attackers often use fake identities or anonymous communication channels. This project leverages supervised machine learning algorithms to identify fraudulent transactions based on patterns in historical data.

Fraudulent activities negatively impact both customers and financial institutions by reducing trust and affecting revenue. Therefore, building an efficient fraud detection system is essential.

---

##  Problem Statement

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.
In this project, you will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.

The dataset is taken from the Kaggle website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.
---
## Technologies Used

* Python 
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Models Used

* Logistic Regression
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest (with Hyperparameter Tuning)

---

##  Project Workflow

1. Data Collection
2. Data Preprocessing

   * Scaling (`Amount`)
   * Dropping unnecessary features (`Time`)
3. Handling Imbalanced Data (SMOTE)
4. Model Training
5. Hyperparameter Tuning (GridSearchCV)
6. Model Evaluation

   * Accuracy
   * Precision & Recall
   * F1-Score
   * ROC-AUC Curve
   * Confusion Matrix
7. Model Comparison
8. Final Model Selection

---

## Performance Metrics

Since this is an imbalanced dataset, the following metrics are prioritized:

* ROC-AUC Score ⭐
* Precision & Recall
* F1-Score
* Confusion Matrix

---

## Results

* Random Forest (Tuned) performed best
* Achieved high ROC-AUC score
* Successfully identified fraudulent transactions with improved recall

---

## How to Run the Project

In order to run the project just download the data from above mentioned source then run any file.

---

## Dataset Source

The dataset is publicly available on Kaggle:

 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Future Improvements

* Deploy as a Streamlit Web App
* Real-time fraud detection system
* Deep Learning models (LSTM, Autoencoders)
* Feature importance analysis
* API integration

---

## Conclusion

This project demonstrates how machine learning can be effectively used to detect fraudulent financial transactions. By handling imbalanced data and optimizing models, we can significantly improve fraud detection systems.

---

## Author

**Areef Baba**
Aspiring Machine Learning Engineer 
