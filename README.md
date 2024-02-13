# Prediction for Credit Card Approval 🏦💳

## Project Overview 📄

This project aims to leverage machine learning techniques 🤖 to predict credit card approval decisions. By analyzing applicants' financial and personal information, we seek to assist financial institutions in making informed decisions, thus reducing the risk of defaults and enhancing customer satisfaction.

## Features 📊

The dataset includes several key features relevant to credit card approval processes:
- `Income`: The applicant's income level.
- `Employment length`: The duration, in years, the applicant has been employed.
- `Account age`: The age of the applicant's bank account in years.
- `Has a car`: Indicates whether the applicant owns a car 🚗.
- `Has a property`: Indicates whether the applicant owns property 🏠.
- `Dwelling`: The type of dwelling the applicant resides in.
- `Is high risk`: A binary target variable indicating if the applicant is considered high risk for credit approval.

## Data Cleaning and Preprocessing ✨

To prepare the data for modeling, we performed several preprocessing steps, including:
- Handling missing values to ensure the integrity of our dataset.
- Detecting and correcting outliers in numerical features to improve model accuracy.
- Encoding categorical variables using one-hot encoding to make the data suitable for our machine learning model.

## Model Training and Evaluation 🛠️

### Model Selection

We chose a Decision Tree Classifier for this task due to its interpretability and effectiveness in handling categorical data. The model was trained with the following parameters:
- Criterion: Entropy
- Max Depth: 10
- Random State: 2

### Training and Testing Data

The data was split into a training set (70%) and a testing set (30%) to evaluate the model's performance accurately.

### Results 📈

The Decision Tree Classifier achieved an accuracy of 98% on both the training and testing sets. However, the classification reports indicate that while the model is highly accurate in identifying low-risk applicants, it struggles with the high-risk category, especially in terms of recall and precision for the minority class.


