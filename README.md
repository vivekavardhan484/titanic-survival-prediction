# titanic-survival-prediction
Machine Learning classification project using the Titanic dataset.
Titanic Survival Prediction

This project predicts which passengers survived the Titanic disaster using machine learning models. It is part of my data science learning journey and demonstrates skills in data cleaning, feature engineering, model training, and evaluation.

📂 Project Overview

The goal of this project is to build models that predict passenger survival on the Titanic. I used Python and scikit-learn to explore the dataset, handle missing values, engineer features, and test different classification models.

🔑 Steps in the Project

Data Cleaning

Filled missing Age with the median.

Filled missing Embarked with the most common value.

Dropped Cabin because too many values were missing.

Feature Engineering

Created FamilySize and IsAlone features.

Extracted passenger titles (Mr, Mrs, Miss, etc.) from the Name column.

Converted categorical variables (Sex, Embarked, Title) into numeric using one-hot encoding.

Model Training

Split data into training and test sets (80/20).

Trained three models:

Logistic Regression

Decision Tree

Random Forest

Hyperparameter Tuning

Used GridSearchCV to find the best parameters for Decision Tree and Random Forest.

Model Evaluation

Compared models using Accuracy, Precision, Recall, and F1 Score.

Checked feature importance for tree-based models.

📊 Results

Logistic Regression: ~81% accuracy

Decision Tree (tuned): ~82% accuracy

Random Forest (tuned): ~81% accuracy

Key features for prediction:

Sex (male/female)

Fare

Age

Pclass

Passenger Title

🛠️ Tools and Libraries

Python

Pandas, NumPy

Matplotlib

Scikit-learn
