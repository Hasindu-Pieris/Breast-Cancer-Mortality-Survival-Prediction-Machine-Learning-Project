# Breast Cancer Mortality & Survival Prediction – Machine Learning Project

This repository contains a complete end-to-end machine learning workflow for predicting breast cancer mortality and estimating survival months using the SEER dataset. The project follows the CRISP-DM methodology and covers data preprocessing, model development, optimisation, and performance evaluation.

## 📌 Project Objectives

* Classify Mortality Status (Alive vs. Dead)

* Predict Survival Months

* Develop, optimise, and compare multiple ML models

* Select and justify the best-performing model

## 🧠 Classification Modelling

* Implemented three supervised learning algorithms:

* Logistic Regression (LR)

* Naïve Bayes (NB)

* K-Nearest Neighbours (KNN)

## ✔ What Was Done

* Data preprocessing

* Stratified train–test split

* Model training and evaluation

* Hyperparameter tuning using GridSearchCV

* Comparative metrics:

* Accuracy

* Precision

* Recall

* F1-score

* AUC-ROC

## ✔ Conclusion

All models were compared using clinical evaluation metrics.
The best-performing model was selected and justified.
A probability-based Ensemble Voting Classifier was also created using the top-performing learners to further enhance predictive accuracy.

## 🌿 Regression Modelling

Two decision tree regression models were developed to estimate survival months:

DT-1: Fully grown Decision Tree

DT-2: Pruned Decision Tree (max_depth = 4)

## ✔ Evaluation Metrics

* Mean Squared Error (MSE)

* Mean Absolute Error (MAE)

* R² Score

* Includes decision tree visualisation and rule-based interpretation.

## 🧪 Tech Stack

* Python

* Pandas, NumPy

* Scikit-learn

* Matplotlib

* Graphviz

* Jupyter Notebook


## 🏁 Outcome

This project demonstrates a full machine-learning pipeline, including:

* Development of three classification models

* Hyperparameter optimisation

* Evaluation using key performance metrics

* Selection of the best clinical prediction model

* Survival month prediction using fully grown and pruned regression decision trees
