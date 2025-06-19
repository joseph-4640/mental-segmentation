# Mental Health Insurance Analysis

## Overview

This project explores mental health insurance data with the primary goal of predicting whether individuals will seek mental health treatment. Leveraging exploratory data analysis (EDA) and machine learning, the project identifies key factors influencing treatment-seeking behavior and develops a predictive model to assess mental health risk factors. The insights gained can be valuable for supporting product development in the mental health insurance domain.

## Objectives

1.  **Analyze Key Factors:** Investigate the relationships between various demographic and behavioral factors and the likelihood of seeking mental health treatment.
2.  **Assess Mental Health Risk:** Develop a method to identify individuals who are more likely to seek mental health treatment based on the available data.
3.  **Build a Predictive Model:** Construct a Random Forest model to predict treatment-seeking behavior.
4.  **Support Product Development:** Provide data-driven insights to inform the development of targeted mental health insurance products and services.

## Data

The project utilizes a dataset containing information on individuals' demographics, occupation, family history, personal habits, and their history and attitudes towards mental health. The target variable is whether an individual seeks mental health treatment.

## Methodology

1.  **Data Preparation:** The raw data was loaded, cleaned, and preprocessed. This involved handling missing values, converting data types, and engineering features where necessary.
2.  **Exploratory Data Analysis (EDA):** Various visualizations and statistical methods were employed to understand the distribution of data, identify patterns, and explore the relationships between different features and the target variable.
3.  **Model Building:** A Random Forest Classifier was chosen for the predictive task. A pipeline was created to handle preprocessing  and model training.
4.  **Hyperparameter Tuning:** GridSearchCV was used to find the optimal hyperparameters for the Random Forest model to improve its performance.
5.  **Model Evaluation:** The trained model was evaluated using standard classification metrics, including accuracy, precision, recall, and F1-score. A confusion matrix was also generated to visualize the model's performance.
6.  **Feature Importance Analysis:** The feature importances from the trained Random Forest model were analyzed to identify the most influential factors in predicting mental health treatment-seeking behavior.

## Results and Findings

*   **Key Influencing Factors:** The EDA and feature importance analysis highlighted several significant factors influencing treatment-seeking, including family history, care options awareness, gender, and self-employment status.
*   **Model Performance:** The Random Forest model achieved a test accuracy of approximately 72%, with reasonable precision and recall for both classes.
*   **Potential Applications:** The findings and the predictive model can be used to segment individuals based on their predicted likelihood of seeking treatment, enabling the development of tailored insurance products and targeted mental health support programs.

## Getting Started

To run this project, you will need to have Python and the necessary libraries installed. The dependencies are listed in the code cells. You will also need access to the dataset used in the project.

## Future Work

*   Explore other machine learning models and techniques to potentially improve predictive performance.
*   Incorporate additional data sources to enrich the analysis.
*   Develop more granular risk assessment categories based on model predictions.
