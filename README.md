Titanic Survival Prediction
Overview
This project is my first real attempt at building a machine learning model to predict passenger survival on the Titanic. Using the Titanic dataset from Kaggle, I performed data cleaning, exploratory data analysis, feature engineering, and trained a Logistic Regression model to classify survivors.

Dataset
The dataset consists of passenger information such as age, sex, ticket class, fare, and other features. It is publicly available from Kaggle’s Titanic competition:
https://www.kaggle.com/c/titanic/data

Approach
Cleaned missing values with median and forward fill

Transformed categorical variables using one-hot encoding

Split data into training and test sets

Trained a Logistic Regression model

Compared predictions against a simple gender-based baseline

Results
Model accuracy: ~38.5% (on the test set)

Gender baseline accuracy: ~36%
This was a modest start, highlighting areas for improvement such as feature selection, hyperparameter tuning, and trying more advanced models.

Future Work
Experiment with different classification algorithms (Random Forest, SVM, etc.)

Hyperparameter tuning to improve accuracy

More feature engineering and analysis

How to Run
Clone the repo

Install required packages: pip install -r requirements.txt

Run the Jupyter notebook titanic.ipynb
