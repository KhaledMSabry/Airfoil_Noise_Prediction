# Airfoil Noise Prediction with Spark ML

## Overview

This project processes a NASA Airfoil Self Noise dataset to build and evaluate a machine learning model that predicts the SoundLevel based on other columns in the dataset. The primary goal is to clean the dataset, create a machine learning pipeline, evaluate the model's performance, and save the trained model for future use.

### Steps:

1. Data Cleaning: Load the dataset, remove duplicate rows, and handle null values to ensure data consistency and reliability.

2. ETL Process: Transform the cleaned data and store it in the parquet format for efficient storage and retrieval.

3. Machine Learning Pipeline: Construct a pipeline with preprocessing stages and a regression model to predict the SoundLevel based on other columns in the dataset.

4. Model Evaluation: Evaluate the model's performance using appropriate metrics to assess its accuracy and effectiveness.

5. Model Persistence: Save the trained model for future use and verify it can be loaded successfully for deployment in real-world applications.
