# Machine Learning Models 

# Predictive-Models

1. Breast-Cancer-Detection

Data: [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data)

Description: [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names)

Overview
This GitHub repository contains a predictive modeling analysis for breast cancer outcomes using machine learning algorithms such as Decision Tree, K-Nearest Neighbors (KNN), Logistic Regression, and Support Vector Machine (SVM). The analysis is based on the Wisconsin Breast Cancer dataset, which includes real-valued features representing mean, standard error, and "worst" values.

Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository and can be accessed here. It consists of feature vectors and binary labels, with the goal of predicting the diagnosis result (malignant or benign) based on ten real-valued features.


---
2. Car-Evaluation-Classification

Overview
This GitHub repository contains the code and data for a machine learning project on car evaluation classification. This project aims to explore and compare different classification techniques, such as Decision Tree, K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machine (SVM), and Naive Bayes. The dataset used for this project includes 1728 records, each representing a car evaluation based on various attributes.

Dataset [Link](http://archive.ics.uci.edu/ml/datasets/Car+Evaluation)

The dataset used in this project is obtained from the UCI Machine Learning Repository and includes seven attributes: buying price, maintenance price, number of doors, capacity in terms of persons, size of luggage boot, estimated safety, and the evaluation of the car (unacceptable, acceptable, good, very good). The attributes are preprocessed and transformed into a binary format, and the target variable is encoded into numerical values.


---
3. Predictive Modeling of Consumer Spending Using Multi-Model Regression

Problem Statement:
Built and compared multiple numeric prediction models—Linear Regression, k-NN, Regression Trees, SVM, Neural Networks, and Ensemble techniques—to forecast consumer spending in response to catalog mailings. Evaluated model performance on both the full dataset (including non-purchasers) and a restricted subset (only purchasers), analyzing the impact of purchase filtering on predictive accuracy. Applied best practices in hyperparameter tuning and normalization to identify the most accurate models.

---
4. Cost-Sensitive Spam Email Detection Using Machine Learning

Dataset [Link](https://archive.ics.uci.edu/dataset/94/spambase)

Problem Statement:
Developed and compared classification models to detect spam emails using the UCI Spambase dataset. Built one model optimized for overall predictive accuracy and a second cost-sensitive model to minimize misclassification costs with a 10:1 penalty ratio (false negatives vs. false positives). Applied and fine-tuned multiple techniques including k-NN, Decision Trees, Naive Bayes, SVM, and Ensemble methods. Evaluated models using nested cross-validation, confusion matrices, ROC curves, and lift charts, and identified the best-performing algorithms based on accuracy, F1-score, AUC, and average cost.


---
5. Evaluating Shallow vs. Deep Neural Networks for Function Approximation


Problem Statement:

Conducted a comparative analysis of neural networks with 1, 2, and 3 hidden layers to evaluate their performance in approximating a non-linear function $f(x) = 2(2\cos^2(x) - 1)^2 - 1$. Simulated 120,000 data points sampled uniformly from $[-2\pi, 2\pi]$, split evenly into training and test sets. Trained networks with varying hidden units and measured performance using mean squared error. The results, visualized across different network depths and parameter scales, revealed that deeper architectures achieved significantly lower errors with fewer units, highlighting their superior representational capacity for complex functions.

![image](https://github.com/user-attachments/assets/3db37477-84e6-4a6a-9da6-2516a3d64cf5)

