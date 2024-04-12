# **Raisin Variety Prediction**

## **Table of Contents**

- [**Importing Data**](#-importing-data)
- [**Analysing Data**](#-analysing-data)
- [**Data Cleaning**](#-data-cleaning)
  - [**Cleaning Outliers**](#1-cleaning-outliers)
  - [**Replacing Outliers with Bounds**](#replacing-outliers-with-bounds)
  - [**Checking Boxplots after Removing Outliers**](#checking-boxplots-after-removing-outliers)
- [**Data Pre-Processing**](#-data-pre-processing)
  - [**Encoding Class**](#1-encoding-class)
- [**Machine Learning**](#-machine-learning)
  - [**Splitting Data**](#splitting-data)
  - [**Standardizing Data**](#standardizing-data)
  - [**Training Different Models**](#training-different-models)
- [**Results and Conclusion**](#-results-and-conclusion)
  - [**Model Performance Comparison**](#model-performance-comparison)
  - [**Conclusion**](#conclusion)
- [**THANK YOU**](#-thank-you)


## **Importing Data**

We begin by importing necessary libraries and loading our dataset.

## **Analysing Data**

We inspect the dataset by checking its dimensions, information, and statistical summaries. Visualizations like KDE plots, pairplots, and heatmaps help us understand the data's distribution and correlations.

## **Data Cleaning**

We address data cleaning tasks such as handling outliers and replacing null values.

1. <u>**Cleaning Outliers:**</u> <br> We identify and replace outliers in the dataset to ensure they don't skew our analysis or modeling.

2. <u>**Replacing Outliers with Bounds:**</u> <br> Outliers are replaced with upper and lower bounds to bring them within an acceptable range.

3. <u>**Checking Boxplots after Removing Outliers:**</u> <br> We visualize boxplots post outlier removal to confirm that the data is now cleaned.

## **Data Pre-Processing**

We prepare the data for modeling tasks by encoding categorical features and splitting it into training and testing sets.

1. <u> **Encoding Class:**</u> <br> We use label encoding to transform the target variable into numerical format.

## **Machine Learning**

We experiment with various machine learning models to identify the best performer for our dataset.

1. <u>**Splitting Data:**</u> <br> We split the dataset into training and testing sets to facilitate model training and evaluation.

2. <u>**Standardizing Data:**</u> <br> Standardization is applied to ensure all features have a similar scale, which aids model performance.

3. <u>**Training Different Models**</u> <br> Several machine learning classifiers are trained and compared based on their accuracy scores.

## **Results and Conclusion**

We summarize the performance of each model and select the best-performing one for predicting raisin varieties.

- <u>**Model Performance Comparison**</u>

An overview of the accuracy scores of different machine learning models.

## **Conclusion**

Based on the evaluation metrics, the best-performing classifier is identified and can be used for further analysis or deployment.

# **THANK YOU**
