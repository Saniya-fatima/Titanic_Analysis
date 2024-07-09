
Titanic Survival Prediction

This project analyzes the Titanic disaster and predicts the survival of passengers using a Logistic Regression model implemented with Scikit-Learn.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This project aims to predict whether a given passenger survived the Titanic disaster using machine learning techniques. The model is trained on the Titanic dataset provided by Kaggle, utilizing features such as age, gender, class, and more.

## Dataset
The dataset used in this project is the [Titanic dataset](https://www.kaggle.com/c/titanic/data) from Kaggle. It contains information about the passengers on the Titanic, including their survival status, age, sex, class, and more.

## Project Structure
The project repository contains the following files:

- `TitanicDisasterAnalysis.ipynb`: Jupyter notebook with the complete analysis and model implementation.
- `README.md`: This readme file.

## Installation
To run this project locally, you need to have Python and Jupyter Notebook installed. You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Exploratory Data Analysis (EDA)
The EDA process involves examining the dataset to understand the relationships between different features and the target variable (survival). Key steps include:

- Handling missing values.
- Visualizing data distributions and relationships.
- Identifying correlations between features.

## Feature Engineering
Feature engineering involves creating new features or modifying existing ones to improve model performance. In this project, the following steps were taken:

- Imputing missing values for Age and Embarked.
- Creating a new feature 'FamilySize' by combining 'SibSp' and 'Parch'.
- Encoding categorical variables like 'Sex' and 'Embarked' using label encoding.

## Modeling
The Logistic Regression model was chosen for this classification problem. The steps involved are:

- Splitting the data into training and testing sets.
- Standardizing the features.
- Training the model using the training set.
- Making predictions on the testing set.

## Evaluation
The model's performance is evaluated using accuracy, precision, recall, and F1 score. Confusion matrix and ROC curve are also plotted to visualize the model's performance.

## Conclusion
The Logistic Regression model provides a baseline for predicting survival on the Titanic. Future improvements could include trying different machine learning algorithms, tuning hyperparameters, and incorporating additional features.


