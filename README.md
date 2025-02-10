# EDA
Exploratory Data Analysis is the process of analyzing and visualizing data to uncover patterns, trends, relationships, and anomalies. It is a crucial step before building machine learning models or making data-driven decisions.

# Description
Vehicle Price Prediction is a data science problem where we analyze historical vehicle data to build insights and estimate the price of used or new vehicles based on various features. EDA (Exploratory Data Analysis) plays a crucial role in understanding the dataset, identifying relationships between features, and improving model performance through feature engineering.

# Requirements
The following Python libraries are required to run this notebook:
matplotlib
numpy
os
pandas
seaborn

# Usage
1. Clone Repository:
   git clone <repo-url>
   cd <repo-folder>
2. Install Dependencies:
   pip install -r requirements.txt
3. Open the Jupyter Notebook:
   jupyter notebook eda.ipynb

# EDA helps in:
1. Understanding the structure and quality of dataset:
   Get insights into the structure, size, and types of data.
   Identify missing values and inconsistencies.

2. Summarize Statistical properties:
   Calculate measures like mean, median, standard deviation, and distribution of variables.

3. Detect outlie and Anomalies:
   Use box plots, histograms, and scatter plots to identify unusual data points.

4. Visual Relationships:
   Use correlation heatmaps, pair plots, and bar charts to explore relationships between features.

5. Feature engineering:
   Create new meaningful features to improve the model’s performance.

# Key Insights from EDA
1. Age & Mileage Impact Price: Older vehicles with higher mileage generally have lower prices.
2. Brand & Transmission Influence: Luxury brands and automatic cars tend to retain higher prices.
3. Outliers Exist: Supercars and rare models have extreme prices compared to the general market.

# Conclusion
EDA plays a crucial role in understanding data patterns and preparing it for predictive modeling. By analyzing key vehicle attributes, we can enhance the accuracy of price prediction models. The insights from EDA guide the feature selection and engineering process, improving machine learning model performance. Future steps include applying regression models like Linear Regression, Decision Trees, Random Forests, and Gradient Boosting to predict vehicle prices more effectively.
