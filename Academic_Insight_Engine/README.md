Academic Insight Engine
The provided Python script outlines a comprehensive process for data acquisition, cleaning, feature engineering, and classification.
Predictstudent performance (Pass/Fail) based on their attributes

Steps:
1. Data Acquisition and Loading
    Google Drive CSV File Link Setup
    Load CSV File into DataFrame
    Display Initial Data Overview
2. Exploratory Data Analysis (EDA)
    Statistical Information and Summary
    Checking for Duplicates
    Handling Missing Data
    Identifying Outliers
3. Data Preprocessing
    Removing Duplicates and Missing Values
    Handling Missing Data for Categorical and Numerical Features
    Outlier Detection and Removal
4. Feature Normalization
    Min-Max Normalization for Numerical Features
5. Categorical Data Encoding
    Label Encoding for Categorical Features
6. Feature Selection and Target Variable Identification
    Identification of Features and Target Variable (Passed)
7. Visualizing Relationships
    Scatter Plots for Quantitative Attributes and Target Variable
    Heatmap for Correlation Analysis
8. Feature Importance
    Mutual Information (Information Gain) Analysis
    Gini Index Based Feature Importance Using Decision Trees
9. Machine Learning - Classification
    Decision Tree Classifier
    Model Evaluation: Accuracy, Confusion Matrix, and Classification Report
10. Clustering
    K-Means Clustering for Binary Classification (Pass/Fail)

Python Libraries
------------------------
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn