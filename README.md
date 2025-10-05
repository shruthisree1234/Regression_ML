# Regression ML Pipeline: Car Mileage Prediction Project

## Overview

This project demonstrates a complete machine learning pipeline using PySpark to predict car mileage (MPG) from multidimensional automotive data. Designed with a focus on real-world data engineering, the workflow bridges robust ETL, advanced regression modeling, performance evaluation, and production model persistence—showing how scalable data science is applied in industry.

## Project Structure

- **Practice_Project.ipynb** — Jupyter notebook with all project stages, code, and explanatory comments.

## Approach

1. **ETL & Data Prep**
   - Load and clean a modified car MPG dataset
   - Remove duplicates, handle missing values, and transform features
   - Store cleaned data in efficient parquet format for scalable processing

2. **Feature Engineering & Modeling**
   - Use PySpark’s `StringIndexer`, `VectorAssembler`, and `StandardScaler` to preprocess and encode features
   - Build a Linear Regression model pipeline from these processed features

3. **Model Evaluation**
   - Evaluate using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R²
   - Access model coefficients and intercept, interpreting their impact on car mileage

4. **Model Persistence & Deployment**
   - Save the trained pipeline model for future batch/inference use
   - Load and apply the persisted model to new (test) data, ready for production or further analysis

## Dataset

- Practice data: Modified version of [UCI Auto MPG dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg)
- Features: Cylinders, Engine Disp, Horsepower, Weight, Acceleration, Model Year, Origin
- Target: MPG (Miles per Gallon)

## Learning Outcomes

- Robust PySpark-based ETL for machine learning
- Building reusable ML pipelines in Spark
- Model evaluation and deployment best practices

## Applications

- Predictive analytics for transportation or manufacturing
- Building scalable regression solutions for large datasets
- Preparation for real-world data engineering and ML workflow interviews

