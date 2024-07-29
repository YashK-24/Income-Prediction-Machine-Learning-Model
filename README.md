# Income-Prediction-Machine-Learning-Model

## About the Project
This project involves building a machine learning model to predict income levels based on various demographic features. The dataset used contains both numerical and categorical data, and the project includes steps for data cleaning, exploratory data analysis (EDA), feature scaling, and model training. The goal is to classify individuals into income categories accurately.

## Table of Contents
1. [Importing Libraries](#importing-libraries)
2. [Data Cleaning](#data-cleaning)
3. [EDA (Exploratory Data Analysis)](#eda)
   - Exploring Numeric Columns
   - Excluding `capital-gain` and `capital-loss` Columns
   - Exploring Categorical Data
   - Bias Towards United States Entries
4. [Splitting Data into Independent and Dependent Variables](#splitting-data-into-independent-and-dependent-variables)
5. [Feature Scaling](#feature-scaling)
6. [ML Model: Logistic Regression model](#ml-model-logistic-regression-model)

## Content
### Importing Libraries
The necessary libraries for data manipulation, visualization, and machine learning are imported.

### Data Cleaning
Handling missing values, correcting data types, and ensuring the dataset is ready for analysis.

### EDA
#### Exploring Numeric Columns
Analyzing numerical features to understand their distribution and relationships.

#### Excluding `capital-gain` and `capital-loss` Columns
These columns are excluded from the dataset as they contain zero values in the majority of entries.

#### Exploring Categorical Data
Investigating the categorical features to understand their distributions and possible impact on the target variable.

#### Bias Towards United States Entries
Noting that the dataset has a majority of entries from the United States, which may introduce bias.

### Splitting Data into Independent and Dependent Variables
Separating the features (independent variables) from the target variable (dependent variable) for model training.

### Feature Scaling
Standardizing the features to ensure they contribute equally to the model training process.

### ML Model: Logistic Regression model
Trained a Logistic Regression model on the processed data to predict income levels,achieving **81%** acurracy score.

## Conclusion
In this project, I've successfully built a machine learning model to predict income levels based on demographic data. The data cleaning and exploratory data analysis steps were crucial in understanding and preparing the dataset for modeling. By using the Logistic Regression model, I'we achieved a robust and interpretable model. Future improvements could include trying different algorithms, performing hyperparameter tuning, and addressing any potential biases in the dataset. This project demonstrates the importance of thorough data preprocessing and the effectiveness of logistic regression in classification tasks.