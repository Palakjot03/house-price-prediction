# House Price Classification using Machine Learning

## Overview

This project applies machine learning techniques to classify residential properties into price categories based on a range of housing features. The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, hyperparameter tuning and performance evaluation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Data Cleaning and Feature Engineering

## Exploratory Data Analysis

## Machine Learning Models

## Results

## Visualisations

### House Price Distribution


![House Price Distribution](images/house-price.png)

This visualisation illustrates the distribution of house price categories within the dataset. Examining the class distribution helped identify potential class imbalance before model training, informing the use of preprocessing techniques such as SMOTE to improve model performance.

### Correlation Heatmap


![Correlation Heatmap](images/heatmap.png)

The heatmap was used during exploratory data analysis to identify relationships between the features and understand which variables were likely to influence the target variable.

#### Confusion Matrix

![Confusion Matrix](images/Randomforest-confusion.png)

The confusion matrix provides a detailed evaluation of the model's classification performance by comparing predicted and actual house price categories. It highlights correctly classified instances as well as areas where the model made misclassifications, offering greater insight than accuracy alone.

#### Model Performance Comparison

![Model Performance Comparison](images/model-comparison.png)

This chart compares the performance of the machine learning models evaluated throughout the project, including K-Nearest Neighbours (KNN), Random Forest, and a Neural Network (MLP). Comparing multiple models enabled the selection of the best-performing approach based on classification accuracy and overall predictive performance.


## Future Improvements
