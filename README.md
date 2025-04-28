# TitanicPrediction
To create a model to with high accuracy to predict whether the passenger had survived the disaster or not
# About
This project uses the classic Titanic dataset to predict survival chances based on passenger details like age, gender, ticket class, and more.
Also focused on both exploratory data analysis (EDA) and model building to make accurate predictions.
# Features
->Data Cleaning and Preprocessing — Handled missing values, removed irrelevant columns, and prepared the data for modeling.
->Feature Encoding — Converted categorical columns (like gender, embarked) into machine-readable numbers using Label Encoding, One-Hot Encoding, and Ordinal Encoding.
->Data Standardization — Scaled numerical features (like age, fare) to have similar ranges, making the model more stable and accurate.
->Exploratory Data Analysis (EDA) — Created box plots to detect outliers, count plots to visualize survival distribution, and bar charts to explore feature relationships.
->Model Building — Trained a Logistic Regression model to predict whether a passenger survived.
->Model Evaluation — Measured model performance using Accuracy, Precision, and F1 Score — all hitting a perfect score of 1.0! ⚡
->Visualization — Used Matplotlib and Seaborn to create clean, attractive graphs that help understand the data better.
# Libraries Used
->numpy — Used for handling numerical operations, creating arrays, and quick math during data processing.
->pandas — Used for reading the dataset, exploring columns, cleaning missing values, and organizing the data.
->matplotlib — Used for basic plotting like bar charts and box plots to visualize survival rates and feature distributions.
->seaborn — Used for making beautiful statistical graphs like count plots and advanced box plots with minimal code.
# sklearn.preprocessing
->LabelEncoder — Converted text categories (e.g., Male/Female) into numbers.
->OneHotEncoder — Applied to features without any order (e.g., Embarked ports) to avoid false rankings.
->OrdinalEncoder — Used when the feature values have a natural order.
->StandardScaler — Standardized numerical features to a similar scale for smoother model training.
->sklearn.linear_model (LogisticRegression) — Built the main classification model to predict survival outcomes.
# sklearn.metrics
->accuracy_score — Checked overall model correctness.
->precision_score — Measured how accurate the positive survival predictions were.
->f1_score — Balanced precision and recall into a single score.
# Steps Followed:
->Loading Data
Imported the Titanic dataset into a pandas DataFrame.

# Data Cleaning
->Filled missing values, dropped unnecessary columns, and made the data neat.

Exploratory Data Analysis (EDA)
->Box Plots to check for outliers.
->Count Plots to understand the survival distribution.
->Bar Charts to see how features affect survival rates.

# Feature Encoding

Transforming text data into numbers so that machine learning algorithms could process them.
->Data Standardization

Scaled numeric columns to ensure all features contributed equally during training.

# Model Training

->Used Logistic Regression to build the prediction model.

Model Evaluation
->Checked how well the model performed — with metrics (Accuracy, Precision, F1 Score) all being 1.0!

# Model Details
Algorithm Used: Logistic Regression

Accuracy: 1.0

Precision: 1.0

F1 Score: 1.0




