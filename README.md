# Predictive Modeling of Coronary Heart Disease using Machine Learning

Author: Tolulope Emuleomo

Date of Creation: 25 April 2024

Coronary Heart Disease (CHD) remains a significant cause of mortality globally. Early diagnosis and intervention are pivotal for effective management and prevention of CHD-related complications. This project aims to develop a machine learning model capable of predicting the presence of CHD in patients based on their demographic information and clinical indicators.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Directions](#future-directions)

## Introduction

CHD is a leading cause of death worldwide, emphasizing the need for accurate predictive models. Traditional methods for assessing CHD risk often lack precision and efficiency. Therefore, this project focuses on leveraging machine learning techniques to enhance CHD risk prediction.

## Problem Statement

The primary objective is to predict the likelihood of CHD using machine learning algorithms. The challenge involves developing a model that accurately identifies patients at risk of CHD based on demographic and clinical factors, surpassing the limitations of traditional risk assessment methods.

## Dataset Description

The dataset comprises various patient attributes, including age, sex, chest pain type, blood pressure, cholesterol levels, and more. These attributes serve as inputs for the predictive models, with the target variable being the presence of CHD.

## Methodology

The project adopts a structured approach:

- **Data Collection and Preprocessing**: Gathering and preprocessing the dataset to handle missing values, normalize features, and encode categorical variables.
- **Exploratory Data Analysis (EDA)**: Exploring the dataset to understand feature-target relationships.
- **Feature Selection**: Identifying relevant features contributing significantly to predicting CHD.
- **Model Development**: Implementing various machine learning algorithms like Logistic Regression, Decision Trees, Random Forests, Support Vector Machines, and Gradient Boosting.
- **Model Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score through techniques like cross-validation.

## Results

- **Random Forest Classifier**: Achieved an F1 Score of 0.911, with a confusion matrix showing 89 true positives, 9 false positives, 14 false negatives, and 118 true negatives.
- **XGBoost Classifier**: Attained an F1 Score of 0.882, with 88 true positives, 10 false positives, 20 false negatives, and 112 true negatives.
- **Decision Tree Classifier**: Yielded an F1 Score of 0.792, with 82 true positives, 16 false positives, 35 false negatives, and 97 true negatives.

## Conclusion

The project successfully developed machine learning models for predicting CHD based on patient demographics and clinical indicators. The Random Forest Classifier exhibited the highest performance, followed closely by the XGBoost Classifier. These models can aid healthcare providers in timely and informed decision-making for CHD prevention and management.

## Future Directions

- Incorporate additional features or data sources for enhanced model performance.
- Explore advanced machine learning techniques or ensemble methods.
- Conduct prospective validation studies for real-world applicability.
- Deploy the final model into production as a user-friendly application or API for healthcare professionals.

This project lays the groundwork for effective CHD risk assessment and management using machine learning, contributing to improved patient outcomes and healthcare decision-making.
