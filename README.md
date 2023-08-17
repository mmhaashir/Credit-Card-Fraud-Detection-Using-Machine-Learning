# Credit Card Fraud Detection Using Machine Learning

This project focuses on utilizing machine learning techniques to detect fraudulent credit card transactions. Credit card fraud is a significant concern for financial institutions and consumers alike. This project aims to develop a model that can accurately identify fraudulent transactions and prevent unauthorized usage.

![cc_image](https://pub.mdpi-res.com/electronics/electronics-11-04003/article_deploy/html/images/electronics-11-04003-g001.png?1670481662)

## Table of Contents

- [**Introduction**](#intro)
- [**Data**](#data)
- [**Model Building**](#model_building)
- [**Evaluation**](#evaluation)
- [**Deployment**](#deployment)
- [**Usage**](#usage)

## Introduction <a name="intro"></a>

Credit card fraud detection involves the use of advanced data analysis and machine learning techniques to identify transactions that are likely to be fraudulent. This project showcases how machine learning models can be trained on historical credit card transaction data to learn patterns of fraudulent activities and make predictions on new transactions.

## Data  <a name="data"></a>
Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The project uses a dataset containing credit card transactions. The dataset includes a mixture of genuine and fraudulent transactions, making it suitable for training and evaluating machine learning models.

## Model Building <a name="model_building"></a>

The project employs the following machine learning algorithms to build a fraud detection model:

1. Logistic Regression
2. Naive Bayes
3. Random Forest
4. Multi-Layer Perceptron

Feature engineering, data preprocessing, and model tuning are performed to optimize the model's performance. 

**SMOTE** is used to handle imbalanced data and generate more synthetic training examples for better fit of the model.

## Evaluation <a name="evaluation"></a>

Following metrics are used to evalue the performance of each of the aforementioned technique in this project:

- Precision
- Recall
- Accuracy
- Confusion Matrix

## Deployment <a name="deployment"></a>

Once the model is trained and evaluated, it can be deployed into a production environment. This can involve integrating the model into existing fraud detection systems used by financial institutions.

## Usage <a name="usage"></a>

1. Clone this repository:
   
   `git clone https://github.com/mmhaashir/credit-card-fraud-detection.git`

3. Install the required dependencies:
   
   `pip install numpy pandas seaborn imblearn random matplotlib` 

3. Run the `Credit_Card_Fraud_Detection.ipynb` file
