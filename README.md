# Performance Comparison of Multiple Machine Learning Algorithms for Iris Flower Classification
# Overview

This repository contains a machine learning project that explores and compares the performance of several classification algorithms on the classic Iris flower dataset. The primary goal is to analyze how different machine learning models perform in terms of classification accuracy and related metrics when identifying Iris species based on physical flower measurements.

The algorithms implemented include popular supervised classifiers such as K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Logistic Regression, Decision Tree, and Random Forest. The results are evaluated using metrics such as accuracy, precision, recall, and F1-score to determine the most effective model for this task.

# Dataset Description

The Iris dataset is a well-known dataset in machine learning containing 150 samples with four numerical features:

 Sepal Length (cm)
 Sepal Width (cm)
 Petal Length (cm)
 Petal Width (cm)

Target classes are:

 Iris-setosa
 Iris-versicolor
 Iris-virginica

 # Algorithms Compared

The following machine learning classifiers are implemented and compared:

K-Nearest Neighbors (KNN) – Majority vote classification. 
GitHub

Support Vector Machine (SVM) – Optimal hyperplane separation. 
GitHub

Logistic Regression – Probability-based linear classifier. 
GitHub

Decision Tree Classifier – Tree-based rule system. 
GitHub

Random Forest Classifier – Ensemble of decision trees. 
GitHub

Each model is trained on the dataset, and results are compared using performance metrics.

# Evaluation Metrics

To assess model performance, the following metrics are computed:

Accuracy Score

Precision

Recall

F1-Score

Confusion Matrix

These metrics help understand how well each algorithm classifies the Iris species and where it performs best.
# System Architecture

<img width="502" height="275" alt="image" src="https://github.com/user-attachments/assets/d7cd3e45-bdbb-449d-a7d5-ad82551fa73d" />

# Output 
Baseline Model Accuracy: Logistic Regression successfully classified the Iris species with a high precision score of ~95%.

<img width="548" height="106" alt="image" src="https://github.com/user-attachments/assets/5e07a887-0074-4986-8c1f-b70ef9e072c4" />

 It compares all the models (SVM, KNN, Naive Bayes, etc.). Comparative Analysis of Machine Learning Algorithms: Performance evaluation of five different classifiers based on accuracy scores.
<img width="357" height="234" alt="image" src="https://github.com/user-attachments/assets/c1d16d66-0186-4800-bd6d-0707fec60d37" />

# Results & Insights

After training each model, accuracy and other metrics are displayed along with graphical comparisons such as bar charts and confusion matrices. These visualizations help decide which model best fits the Iris classification task.

# References
[1]        R. Rajab Asaad & A. M. Abdulazeez, Comprehensive Classification of Iris Flower Species: A Machine Learning Approach, Indonesian Journal of Computer Science, 2024 — compares SVM, RF, KNN, etc. on Iris dataset.

[2]        D. Rajkumar, J. Sreerambabu & S. Kalidasan, IRIS Species Predictor, IJRASET Journal, 2022 — classification of Iris flowers using scikit‑learn.

[3]      Uppalapati Gowtham et al., Iris Dataset Classification Using Machine Learning, IJSRED, 2025 — case study using K‑Nearest Neighbors.

[4]      T. Kirubarani & K. Kaviselvan, Iris Flower Classification using Support Vector Machine and Web Deployment with Flask, IJMRSET, 2025 — integrates SVM with a web interface. 

[5]     Classification of Iris Flower by Random Forest Algorithm, Advances in AI Research, 2022 — evaluates RF, SVM & ANN performance.

[6]      Iris flower classification and Fake News Detection using Machine Learning, RCC Institute Project Report — pattern recognition for Iris classification. 

[7]     Sarika, Iris flower classification project: Leveraging machine learning for precise botanical identification, The Pharma Journal, 2019 — deep learning vs classical ML. 

[8]      ML Fundamentals: Classification with Iris Dataset, interactive educational overview — foundational background. 
