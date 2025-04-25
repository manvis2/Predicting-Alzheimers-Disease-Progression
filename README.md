# Predicting Alzheimer's Disease Progression
This project explores the application of machine learning to model Alzheimer’s disease progression using longitudinal clinical data. Developed as my capstone thesis for the Master of Public Health in Data Science at the University of Chicago, the goal was to predict the rate of cognitive decline in Alzheimer’s patients based on demographic, health, and behavioral indicators.

The dataset used in this study was provided by the National Alzheimer’s Coordinating Center (NACC) Uniform Data Set (UDS), which includes detailed records from over 130 Alzheimer's Disease Research Centers across the U.S. The final analytic dataset included 2,654 patients with an average of 7.5 visits per person. The outcome variable 'rate of disease progression' was derived from changes in the Clinical Dementia Rating (CDR) global score across patient visits.

-----
The data was preprocessed to remove high-missingness columns, impute remaining values, and aggregate longitudinal records into patient-level summaries. Two machine learning models were implemented - Random Forest and XGBoost, chosen for their ability to model non-linear interactions and handle mixed feature types. Hyperparameter tuning was conducted using Optuna, and models were evaluated using R-squared and mean squared error (MSE).

The best-performing model, Random Forest, explained approximately 46% of the variability in progression rate. The most predictive features included patient independence level, body mass index, and duration of follow-up. The analysis also found evidence that disease progression tends to slow over time, and that physical and mental health factors, particularly BMI and anxiety, are associated with faster decline.

This project contributes to public health research by demonstrating how machine learning can support earlier identification of high-risk patients, inform care planning, and improve clinical resource allocation. 

This repository contains both the full capstone written report and the Jupyter Notebook used for data preprocessing, modeling, and visualization. The notebook is fully executed and self-contained for reproducibility. All code was developed in Python and organized to reflect the workflow detailed in the written report.

