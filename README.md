# URL Phishing Detection Project

This repository contains Python code for a machine learning model that detects phishing URLs. The model is implemented using XGBoost classifier, trained on a dataset of URLs to classify them as either phishing, suspicious, or legitimate.

## Project Overview

The goal of this project is to develop a machine learning model capable of accurately identifying phishing URLs. Phishing URLs are malicious links designed to deceive users into disclosing sensitive information, such as passwords or credit card details, by masquerading as legitimate websites.

## Dataset

The dataset used for training and evaluation is stored in a CSV file named `phishing_urls.csv`. It contains a list of URLs along with their corresponding labels indicating their legitimacy.

### Features
- URL: The web address of the website
- Label: Label indicating the legitimacy of the URL
  - 1: Legitimate
  - 0: Suspicious
  - -1: Phishing

## Prerequisites

Before running the code, ensure you have the following libraries installed:
- Matplotlib
- Seaborn
- Pandas
- NumPy
- XGBoost

You can install these libraries via pip:

```
pip install matplotlib seaborn pandas numpy xgboost
```

## Results

The model's performance is evaluated using various metrics, providing insights into its effectiveness in detecting phishing URLs.

### Cross-Validation Results

The model is trained using k-fold cross-validation, with the dataset split into multiple folds for training and evaluation. Here are the accuracy scores for the first two folds:

- Fold 1: 96.8%
- Fold 2: 97.2%

These accuracy scores demonstrate the model's ability to accurately classify URLs as phishing, suspicious, or legitimate.

Additionally, the results of individual predictions on the test dataset are presented, allowing for further analysis of the model's behavior.

---
