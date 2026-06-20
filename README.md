Laptop Price Prediction using Machine Learning
Overview

This project focuses on analyzing laptop specifications and predicting laptop prices using Machine Learning techniques.

The project covers the complete data science workflow:

Data Cleaning
Feature Engineering
Exploratory Data Analysis (EDA)
Data Preprocessing
Feature Encoding
Regression Modeling
Model Evaluation

The goal is to estimate the market price of a laptop based on its hardware specifications.

Business Problem

Laptop prices vary significantly depending on hardware configurations and brand reputation.

The objective of this project is to build a predictive model capable of estimating laptop prices using technical specifications such as:

Processor
RAM
Storage
GPU
Display Features
Operating System
Dataset Features
Feature	Description
Company	Laptop Manufacturer
TypeName	Laptop Category
Inches	Screen Size
ScreenResolution	Screen Resolution
CPU	Processor Details
RAM	Installed RAM
Memory	Storage Configuration
GPU	Graphics Card
OpSys	Operating System
Weight	Device Weight
Price	Target Variable
Data Cleaning

The preprocessing stage included:

Removing unnecessary columns
Handling missing values
Converting data types
Cleaning textual information
Standardizing categorical values
Feature Engineering

Several new features were extracted:

CPU Brand

Examples:

Intel
AMD
GPU Brand

Examples:

Nvidia
AMD
Intel
Storage Breakdown

Memory information was separated into:

SSD Capacity
HDD Capacity
Hybrid Storage
Flash Storage
Display Features

Extracted:

IPS Display
Touchscreen Support
Resolution Category
Exploratory Data Analysis

Key analyses included:

Price Distribution
RAM vs Price
Company vs Price
TypeName vs Price
Screen Size vs Price
Correlation Analysis
Machine Learning Model
Linear Regression

A regression model was trained to predict laptop prices based on engineered features.

Evaluation Metrics

The model was evaluated using:

R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Future Improvements
Random Forest Regressor
XGBoost Regressor
Hyperparameter Tuning
Feature Selection
Streamlit Deployment
