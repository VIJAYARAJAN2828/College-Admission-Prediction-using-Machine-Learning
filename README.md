# College-Admission-Prediction-using-Machine-Learning
README.md

College Admission Prediction

This repository contains a machine learning model designed to predict the likelihood of a student's admission to a college based on various factors such as GRE scores, TOEFL scores, undergraduate GPA, and research experience.

Dataset:

The dataset consists of the following features:

Serial No.: A unique identifier for each record.
GRE Score: The student's score on the Graduate Record Examinations.
TOEFL Score: The student's score on the Test of English as a Foreign Language.
University Rating: A rating of the university where the student graduated from.
SOP: The student's Statement of Purpose score.
LOR: The student's Letter of Recommendation score.
CGPA: The student's undergraduate grade point average.
Research: A binary indicator of whether the student has research experience.
Chance of Admit: The target variable, representing the probability of admission.
Model Selection and Training:

Several classification algorithms were explored and compared to select the best model for this task:

Logistic Regression
Decision Tree
Gaussian Naive Bayes
Tuned Decision Tree
Ada Boost
Model Evaluation:

The performance of each model was evaluated using the following metrics:

Accuracy Score
F1 Score
f1-micro
f1-macro
f1-weighted
Results:

Based on the evaluation results, the Decision Tree model achieved the highest accuracy score of 1.00000 on the training set and 0.80000 on the test set. It also demonstrated strong performance on the F1 score and other metrics..
