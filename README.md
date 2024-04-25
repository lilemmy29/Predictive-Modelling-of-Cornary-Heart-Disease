# Project Report: Predictive Modeling of Coronary Heart Disease using Machine Learning

## Introduction

Coronary heart disease (CHD) is a leading cause of death worldwide, with millions of individuals affected annually. Traditional diagnostic methods, such as electrocardiograms (ECGs), are often expensive, time-consuming, and may not be accessible in smaller clinics. The advent of machine learning (ML) offers a promising alternative for early detection and risk assessment of CHD, leveraging patient data to predict disease presence with high accuracy. This project aims to develop a predictive model for CHD using ML techniques, focusing on the application of various algorithms to analyze patient demographics and clinical indicators.

## Objective

The primary objective of this project is to create a reliable ML model capable of accurately predicting the presence of CHD in patients based on their demographic information and clinical indicators. This model will assist healthcare providers in making timely and informed decisions for the prevention and management of coronary heart disease.

## Methodology

### Data Collection and Preprocessing

The dataset used for this project contains patient attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved during exercise, exercise-induced angina, oldpeak (ST depression induced by exercise relative to rest), and the slope of the peak exercise ST segment. The data was preprocessed to handle missing values, normalize features, and encode categorical variables.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the relationships between different features and the target variable (presence of CHD). This step involved visualizing the data and identifying any patterns or anomalies that could influence the model's performance.

### Feature Selection

Relevant features contributing significantly to predicting CHD were identified through feature selection techniques. This step ensured that the model focuses on the most informative attributes, improving its predictive accuracy.

### Model Development

Various ML algorithms were implemented to develop predictive models, including logistic regression, decision trees, random forests, support vector machines, and gradient boosting. Each algorithm was trained and tested on the dataset to evaluate its performance.

### Model Evaluation

The performance of each model was evaluated using metrics such as accuracy, precision, recall, and F1-score. Techniques like cross-validation were employed to ensure the robustness of the models.

## Results

### Random Forest Classifier

The Random Forest Classifier achieved an F1 Score of 0.911, indicating a high level of accuracy in predicting CHD. The feature importance scores revealed that age, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, max heart rate, exercise angina, oldpeak, and ST slope were the most influential factors in predicting CHD.

### XGBoost Classifier

The XGBoost Classifier achieved an F1 Score of 0.882, slightly lower than the Random Forest Classifier but still indicating a strong predictive performance. The feature importance scores highlighted that age, chest pain type, cholesterol, fasting blood sugar, max heart rate, exercise angina, oldpeak, and ST slope were significant in predicting CHD.

### Decision Tree Classifier

The Decision Tree Classifier achieved an F1 Score of 0.792, indicating a moderate level of accuracy in predicting CHD. The feature importance scores showed that age, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, max heart rate, exercise angina, oldpeak, and ST slope were the most influential factors.

## Conclusion

The project successfully developed predictive models for CHD using ML techniques, demonstrating the potential of these algorithms in healthcare for early detection and risk assessment. The Random Forest Classifier and XGBoost Classifier showed the highest accuracy, suggesting that these models could be valuable tools for healthcare providers in the early diagnosis and management of CHD. Further research and refinement of these models could lead to more accurate and efficient CHD prediction systems.

## Additional Resources

A Jupyter Notebook has been included with this project to provide a detailed walkthrough of the data analysis and model development process. This notebook integrates code, output, and explanations into a single document, making the project transparent, understandable, repeatable, and shareable. The dataset used for this project is also provided for further analysis and replication of the results.

#### Author: Tolulope Emuleomo
#### Date: 25 April 2024
