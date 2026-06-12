# House Price Prediction using Machine Learning

## Introduction

This project builds and evaluates machine learning models for predicting house prices based on the House Prices - Advanced Regression Techniques dataset. The dataset contains various features describing houses, such as area, overall quality, location, garage, basement, and other amenities.

## Project Objectives

* Preprocess real estate data containing both numerical and categorical variables.
* Handle missing values, apply One-Hot Encoding, and standardize the data.
* Apply PCA and TruncatedSVD for dimensionality reduction.
* Build and evaluate regression models to predict `SalePrice`.
* Perform data clustering using K-Means, GMM, and DBSCAN.
* Convert the regression problem into a classification problem by dividing `SalePrice` into price ranges.
* Compare classification models such as KNN, Gaussian Naive Bayes, and Multinomial Logistic Regression.

## Dataset

This project uses the House Prices - Advanced Regression Techniques dataset.
The target variable is `SalePrice`, which represents the selling price of a house.

## Folder Structure

```text
House-Price-Prediction-ML/
├── data/                  # Train/test data
├── notebooks/             # Experimental notebooks
├── README.md              # Project description
├── requirements.txt       # List of required libraries
└── data_description.txt   # Description of dataset features
```

## Workflow

1. Explore the initial dataset.
2. Handle missing values.
3. Encode categorical variables using One-Hot Encoding.
4. Standardize numerical variables using StandardScaler.
5. Reduce data dimensionality using PCA and TruncatedSVD.
6. Build regression models.
7. Perform data clustering.
8. Convert the problem into a classification task.
9. Evaluate and compare the results.

## Models Used

### Regression

* Linear Regression
* KNN Regression
* Ridge Regression
* MLP Regression

### Clustering

* K-Means
* Gaussian Mixture Model
* DBSCAN

### Classification

* KNN Classification
* Gaussian Naive Bayes
* Multinomial Logistic Regression

## Key Results

* PCA helps reduce the dimensionality of the data while preserving most of the important information.
* PC1 has a strong correlation with `SalePrice`, which is useful for analysis and visualization.
* K-Means produces more stable clustering results than GMM and DBSCAN in this project.
* Multinomial Logistic Regression achieves the best performance in the house price range classification task.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## How to Run the Project

Install the required libraries:

```bash
pip install -r requirements.txt
```
