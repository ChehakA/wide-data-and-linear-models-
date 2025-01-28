This repository contains a binary classification model to predict the disease type (UCEC: uterine corpus endometrial carcinoma) from transcriptomics data using linear models. The dataset consists of features and labels for 554 patients, with the training set comprising 80% of the data (444 patients) and the test set comprising 20% (110 patients). The goal is to classify tumor grade (II- vs. III+) based on gene expression data.

Tasks and Objectives:
Binary Classification: The goal is to predict tumor grade (II- or III+) using features derived from transcriptomics data. The model outputs a binary classification (0 or 1).
Model Development: Implement a pipeline to train various linear models (e.g., linear regression, logistic regression, ridge regression, LASSO) on the training data.
Regularization: Study the effect of different regularization parameters (e.g., for ridge and LASSO) on model performance and select the best-performing model.
Model Evaluation: Assess the classification performance using common evaluation metrics such as accuracy and F1-score on the test set.
Random Guessing Comparison: Compare the best model's performance to random guessing (randomized labels) to gauge the predictive power of the model.
Feature Importance: Analyze the importance of individual genes in making model predictions. Identify which genes are most significant in classifying the tumor grade.
Visualization: Explore the dataset visually to assess whether it’s possible to distinguish between the two groups (tumor grades II- vs. III+) based on the features.
