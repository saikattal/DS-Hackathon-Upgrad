# DS-Hackathon-Upgrad
Multi-Class Product Category Classification
This repository contains a project focused on multi-class classification of product descriptions into their respective categories using machine learning and deep learning techniques.

Project Overview
The goal of this project is to accurately classify products based on their descriptions into predefined categories. The dataset used for this project includes various features, but the primary feature used for classification is the product description.

Dataset
The dataset consists of the following files:

train_product_data.csv: Training data with 15,000 records and 15 features.
test_data.csv: Test data used for evaluating the model.
test_results.csv: Results file to store the predictions.
Key Columns:
description: Detailed information about the product.
product_category_tree: The target column representing the product's category.

Project Structure

Getting Started
Prerequisites
Ensure you have the following libraries installed:

numpy
pandas
scikit-learn
tensorflow
xgboost
matplotlib
seaborn

Data Preprocessing
The data preprocessing involves cleaning the text data, removing irrelevant words, and handling missing values.

Feature Engineering
The feature engineering step includes converting text data into numerical features using CountVectorizer and TF-IDF

Results
Logistic Regression and SVC model achieved an weighted average score of 83%.
The Deep Learning model achieved a weighted average score of 84%.

Note on Misclassifications
A significant number of misclassifications were observed in the 'Baby Care' category, which was often predicted as 'Home Decor & Festive Needs'. This might be due to overlapping product descriptions in these categories.

Addressing Class Imbalance
Undersampling technique was used to handle class imbalance






