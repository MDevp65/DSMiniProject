# Data Science mini Project

This repository contains a data science project focused on basics of Data Science on Titanic dataset. The project encompasses data loading, handling missing values, exploratory data analysis (EDA), and a basic machine learning model for prediction.

## Overview

The primary objective of this project is to explore the Titanic dataset, preprocess it, and build a simple machine learning model to predict whether a passenger survived the tragic sinking. The analysis involves understanding the characteristics of the passengers and identifying potential factors influencing survival.

## Files

* **`titanic.csv`**: The core dataset used in this project, containing information about Titanic passengers and their survival status.
* **`LoadData_ImputeMissingVal.ipynb`**: A Jupyter Notebook detailing the workflow, including:
    * **Data Loading:** Loading the `titanic.csv` file using pandas.
    * **Handling Missing Values:** Implementing various imputation techniques such as mean, median, mode, and a machine learning-based imputer to address missing data in different features.
* **`Visualization.ipynb`**: A Jupyter Notebook detailing the workflow, including:
    * **Exploratory Data Analysis (EDA):** Visualizing data distributions, relationships between features, and patterns related to survival using libraries like matplotlib and seaborn. This includes creating various plots (e.g., histograms, bar plots, scatter plots) to gain insights from the data.
* **`MachineLearning.ipynb`**: A Jupyter Notebook detailing the workflow, including:
    * **Basic Machine Learning Model:** Building and training a Logistic Regression model using scikit-learn to predict passenger survival based on the processed features.

## Key Steps in the Notebook

The `titanic.ipynb` file walks through the following key stages:

* **Data Loading and Initial Inspection:** Loading the dataset and examining its basic structure and information.
* **Missing Value Imputation:** Demonstrating different strategies for handling missing data, including:
    * Imputation using the mean.
    * Imputation using the median.
    * Imputation using the mode.
    * Imputation using a machine learning-based imputer (e.g., `IterativeImputer` from scikit-learn).
* **Exploratory Data Analysis (EDA):**
    * Analyzing the distribution of numerical and categorical features.
    * Visualizing the relationship between different features and the 'survived' target variable using matplotlib and seaborn
* **Basic Logistic Regression Model:**
    * Preparing the data for the model (e.g., encoding categorical features, handling potential multicollinearity).
    * Splitting the data into training and testing sets.
    * Training a Logistic Regression model using scikit-learn.
    * Evaluating the basic performance of the model on the test set (e.g., using accuracy).

## Libraries Used

* **pandas**: For data manipulation and reading the CSV file.
* **numpy**: For numerical operations.
* **matplotlib**: For creating basic plots and visualizations.
* **seaborn**: For enhanced and more informative statistical visualizations.
* **scikit-learn**: For machine learning tasks, including imputation (`SimpleImputer`, `IterativeImputer`), data preprocessing (e.g., `LabelEncoder`, `OneHotEncoder`), model building (`LogisticRegression`), and model evaluation.

## Further Exploration

This project provides a foundational understanding of the Titanic dataset and a basic prediction model. Potential next steps could include:

* More advanced feature engineering.
* Exploring other machine learning models.
* Hyperparameter tuning to improve model performance.
* More in-depth analysis of the factors influencing survival.

## Contributing

Contributions to this project are welcome. Feel free to suggest improvements or report issues.
