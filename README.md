This repository contains a data preprocessing pipeline and machine learning model to predict flight prices based on various features such as airline, flight route, departure time, and others. The model uses a Random Forest Regressor to predict the flight prices from historical data.

Requirements
Python libraries:
-----------
pandas
numpy
matplotlib
seaborn
plotly
cufflinks
scikit-learn
pickle

You can install the required libraries using:
-----------------------------------------------
pip install pandas numpy matplotlib seaborn plotly cufflinks scikit-learn




Code Overview
1. Data Import and Exploration
This code reads the Excel file Data_Train.xlsx, explores the dataset by displaying the first and last few rows, checking for missing values, and understanding the data types.

2. Data Preprocessing
Handling Missing Values
Converting Dates
Feature Engineering

3. Feature Extraction
Extracting Hour and Minute
Encoding Categorical Variables

4. Data Visualization
Visualizing Flight Departure Times

5. Model Building - Random Forest Regressor

6. Saving the Model
The trained model is saved using pickle


