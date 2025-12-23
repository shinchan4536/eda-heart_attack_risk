# eda-heart_attack_risk
Heart Attack Risk Analysis in Youngsters (18-30) 
*Exploratory Data Analysis & Health Insight Visualization*

Project Overview :
This project performs a comprehensive Exploratory Data Analysis (EDA) on health metrics to identify the primary drivers of heart attack risk among individuals aged 18–30. By leveraging Python's data science ecosystem, I transformed raw medical data into actionable visual insights to support early cardiac health awareness.

Tech Stack :
Environment: Google Colab
Languages: Python
Libraries: Pandas & NumPy: For data cleaning, handling missing values, and feature manipulation.
Matplotlib & Seaborn: For generating statistical visualizations like heatmaps, histograms, and boxplots.

Key Analysis Phases :
Data Profiling: Used .info() and .describe() to understand the statistical distribution and data types of health indicators.
Data Cleaning: Identified and handled null values to ensure the integrity of the correlation analysis.
Correlation Study: Created a correlation heatmap to determine how variables like Cholesterol, Blood Pressure, and Stress Levels impact the heart attack risk score.
Demographic Deep-Dive: Specifically filtered the dataset to analyze trends within the 18–30 age bracket.

Key Insights :
Cholesterol Correlation: Individuals with cholesterol levels above 200 mg/dL showed a significant increase in risk indicators.
Blood Pressure Trends: Systolic blood pressure proved to be a more volatile indicator of acute risk than diastolic pressure in the target age group.
Feature Importance: Visualized which lifestyle factors (Smoking, Exercise) had the most drastic effect on the target outcome.

How to Use :
Open in Colab: You can view the live analysis by opening the EDA_PROJECT.ipynb file directly in Google Colab.
