1. Project Overview:

This project analyzes food delivery data to identify the key factors affecting delivery delays. The analysis includes data cleaning, descriptive statistics, outlier detection, relationship analysis, hypothesis testing, and business recommendations.

The objective is to understand how factors such as distance, weather, traffic conditions, preparation time, and courier experience influence delivery performance.

2. Dataset Information:

The dataset contains 1000 food delivery records with the following features:

Order_ID
Distance_km
Weather
Traffic_Level
Time_of_Day
Vehicle_Type
Preparation_Time_min
Courier_Experience_yrs
Delivery_Time_min


3. Tools and Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
Project Workflow
Phase 1: Data Cleaning
Loaded dataset
Checked data types
Identified missing values
Handled missing values using Mode and Mean
Checked duplicate records

4.  Descriptive Statistics

Calculated:

Mean
Median
Mode
Standard Deviation
Variance
Quartiles
Phase 3: Outlier Detection

Techniques used:

Box Plot
IQR Method
Z-Score Method

5. Relationship Analysis

Studied relationships between:

Distance vs Delivery Time
Traffic Level vs Delivery Time
Weather vs Delivery Time
Preparation Time vs Delivery Time

Techniques used:

Scatter Plots
Correlation Matrix
Heatmap
Phase 5: Hypothesis Testing

ANOVA Test

Null Hypothesis (H₀):
Weather does not affect delivery delay.

Alternative Hypothesis (H₁):
Weather significantly affects delivery delay.

6. Result:

F-statistic = 8.636
p-value = 0.00019

Since p-value < 0.05, the null hypothesis was rejected.

7. Conclusion:
Weather has a significant impact on delivery delays.

8. Key Findings:

Average delivery time is 56.73 minutes.
Distance is the strongest factor affecting delivery delays.
Longer preparation times increase delivery duration.
High traffic conditions lead to longer delivery times.
Adverse weather conditions increase delivery delays.
Courier experience has a weak negative correlation with delivery time.
Several delivery records were identified as outliers.

