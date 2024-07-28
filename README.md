# Predictive Analysis for Employee Retention at Salifort Motors

## Project Overview

This repository contains the capstone project of the Google Advanced Data Analytics course. The goal of the project is to analyze a dataset provided by the HR department of Salifort Motors and build predictive models to identify factors that may lead employees to leave the company. By predicting potential employee turnover, the company can take proactive measures to improve employee satisfaction and retention.

## Introduction

Employee turnover is a major challenge for many organizations. High turnover rates can lead to increased recruitment costs and the loss of valuable knowledge and skills. In this project, we aim to use data analysis to predict whether an employee will leave the company and identify the key factors that influence his or her decision.

## Dataset Description

The dataset used in this project was collected by the HR department of Salifort Motors and includes various features such as:

- `satisfaction_level`
- `last_evaluation`
- `number_project`
- `average_monthly_hours`
- `tenure`
- `work_accident`
- `promotion_last_5years`
- `departments`
- `salary`

## Data Preprocessing

Several preprocessing steps were applied to clean and prepare the data for analysis:

- Checking for missing values
- Handling duplicate entries
- Identifying and treating outliers
- Encoding categorical variables
- Splitting the data into training and testing sets

## Exploratory Data Analysis (EDA)

EDA was performed to understand the data set and identify key patterns and trends. Visualizations were used to explore the relationships between characteristics and employee turnover. Key findings include:

- Employees with extreme working hours (very high or very low) are more likely to leave
- Satisfaction level and last evaluation scores are significant predictors of turnover
- Employees with 3-4 projects have the lowest turnover rates

## Model Selection and Training

Two types of models were considered for this project:

1. **Logistic Regression**
2. **Decision Tree-based Machine Learning (Random Forest)**

After preprocessing and feature engineering, both models were trained and evaluated on the dataset. The importance of the features was analyzed to understand the impact of each feature on the prediction.

## Feedback and Contributions

I welcome feedback and contributions from the community. If you have any suggestions or would like to contribute to the project, please open an issue or submit a pull request on my [GitHub repository](https://github.com/sbaglieri13/Predictive-Analysis-for-Employee-Retention-at-Salifort-Motors).
