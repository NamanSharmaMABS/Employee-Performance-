# Employee-Performance- 
**Employee Data Analysis Project**: (Presented by NIkhil,Manik, Anuj, Naman Sharma)
**Overview**
This project focuses on analyzing employee data using Python. Key tasks include adding new calculated columns (Efficiency and HourlyIncome), creating a correlation matrix, detecting outliers, and visualizing the distribution of key metrics.

**Objectives**
Data Augmentation:

**Added two new columns:**
Efficiency: A performance indicator calculated based on TasksCompleted, HoursTrained, and OvertimeHours.
HourlyIncome: Derived by dividing MonthlyIncome by total working hours.
**Correlation Matrix:**

Created a heatmap to explore correlations between key variables in the dataset.
**Outlier Detection:**

Identified outliers in all numeric columns using statistical techniques such as the Interquartile Range (IQR) method.
**Key Metric Distributions:**

Visualized distributions for:
MonthlyIncome
PerformanceRating
Efficiency
AttendanceRate
Tools and Libraries
**Python**
Pandas: Data manipulation
Matplotlib & Seaborn: Data visualization
NumPy: Numerical computations
Scipy: Statistical analysis
Key Features
1. Correlation Matrix
Analyzed relationships between variables using a heatmap (see image above).
2. Outlier Detection
Used the IQR method to identify and visualize outliers in key metrics.
3. Metric Distribution
Generated histograms and KDE plots to understand the distributions of key metrics.
Key Results
**Correlation Insights:**

HourlyIncome strongly correlates with MonthlyIncome (r = 0.70).
Efficiency has a moderate correlation with HoursTrained (r = 0.36).
Outliers:

Detected in columns like MonthlyIncome and OvertimeHours.
Distribution Analysis:

Key metrics showed varying patterns, with Efficiency having a right-skewed distribution.
