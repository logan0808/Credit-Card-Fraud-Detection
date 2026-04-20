# Credit Card Fraud Detection using Machine Learning

** Author:** Shehu Olakunle Yunus  
**📅 Completed:** 20th April 2026  
**🔗 GitHub:** https://github.com/logan0808  

🚀 End-to-end machine learning project for detecting fraudulent credit card transactions using imbalanced data.
 End-to-end machine learning project for detecting fraudulent transactions using imbalanced data.

---

## Overview

This project builds a machine learning model to identify fraudulent credit card transactions based on transaction features.

---

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Workflow

1. Data Loading & Cleaning  
2. Exploratory Data Analysis  
3. Feature Scaling  
4. Train-Test Split  
5. Handling Imbalanced Data  
6. Model Training  
7. Model Evaluation  
8. Feature Importance Analysis  

---

## Results

- Random Forest ROC-AUC: ~0.97  
- Strong recall for fraud detection  
- Effective handling of imbalanced dataset  

---
## View Notebook

 https://nbviewer.org/github/logan0808/Credit-Card-Fraud-Detection/blob/main/Credit-Card-Fraud-Detection.ipynb
---

## Model Output

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix_1.png)

### Feature Importance
![Feature Importance](images/feature_importance_2.png)

---

## Key Insights

- Fraud detection is a highly imbalanced problem  
- Recall is more important than accuracy  
- Random Forest performs better than Logistic Regression  

---

## Limitations

- Dataset features are anonymized  
- Model is not deployed in real-time  
- External factors not included  

---

## Future Improvements

- Use advanced models (XGBoost, LightGBM)  
- Deploy model as API  
- Integrate real-time streaming data  

---

## Use Cases

- Detect fraudulent transactions  
- Improve banking security  
- Reduce financial losses  

---

## Dataset

Download the dataset from Kaggle:  
https://www.kaggle.com/mlg-ulb/creditcardfraud  

Place the file `creditcard.csv` in the root directory of this project.

---
## How to Run

```bash
git clone https://github.com/logan0808/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

pip install -r requirements.txt
