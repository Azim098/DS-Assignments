ABC Company Employee Data Analysis
Project Overview

This project analyzes the ABC Company Employee Dataset, which contains 458 employee records and 9 attributes. The objective is to preprocess the dataset, perform exploratory data analysis (EDA), visualize key findings, and derive meaningful business insights using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The analysis provides a clear understanding of employee distribution, salary expenditure, age demographics, and the relationship between employee age and salary.

Objectives
Perform data preprocessing to improve data quality.
Analyze employee distribution across different teams.
Categorize employees based on their job positions.
Identify the predominant age group among employees.
Determine which team and position incur the highest salary expenditure.
Examine the relationship between employee age and salary.
Present findings using appropriate visualizations.
Dataset Information
Dataset: ABC Company Employee Dataset
Number of Records: 458
Number of Columns: 9
Dataset Features
Name
Team
Number
Position
Age
Height
Weight
College
Salary
Data Preprocessing

Before performing the analysis, the dataset was cleaned to ensure consistency.

Preprocessing Steps
Imported the dataset using Pandas.
Checked for missing values and duplicate records.
Replaced the values in the Height column with randomly generated values ranging from 150 cm to 180 cm, as specified in the project requirements.
Verified that the dataset was ready for analysis after preprocessing.
Analysis Performed
1. Employee Distribution Across Teams
Calculated the number of employees in each team.
Computed the percentage contribution of each team relative to the total workforce.
Identified teams with the highest and lowest employee counts.
Visualization
Bar Chart showing employee count by team.
2. Employee Distribution by Position

Employees were grouped based on their playing positions.

Positions include:

PG (Point Guard)
SG (Shooting Guard)
SF (Small Forward)
PF (Power Forward)
C (Center)
Visualization
Pie Chart illustrating the percentage of employees in each position.
3. Predominant Age Group

Employees were categorized into age groups:

19–25
26–30
31–35
36–40
41–50

The distribution was analyzed to determine the most common age group within the company.

Visualization
Bar Chart representing employee count in each age group.
4. Salary Expenditure Analysis

Salary data was aggregated to determine:

Total salary expenditure by team.
Total salary expenditure by employee position.

This analysis helps identify departments and positions with the highest payroll expenses.

Visualization
Bar Chart for salary expenditure by team.
Bar Chart for salary expenditure by position.
5. Correlation Between Age and Salary

The Pearson correlation coefficient was calculated to examine whether employee age influences salary.

A scatter plot was generated to visualize the relationship between these two variables.

Visualization
Scatter Plot of Age vs Salary.
Graphical Representations

The project includes the following visualizations:

Bar Chart – Employee Distribution Across Teams
Pie Chart – Employee Distribution by Position
Bar Chart – Predominant Age Group
Bar Chart – Salary Expenditure by Team
Bar Chart – Salary Expenditure by Position
Scatter Plot – Age vs Salary Correlation

These graphs provide a clear visual interpretation of the dataset and support the analytical findings.

Key Insights
The dataset contains 458 employees across multiple teams.
Employee distribution varies among teams, with some teams having significantly larger workforces.
Shooting Guard (SG) is the most common employee position.
Most employees belong to the 19–25 years age group, indicating a relatively young workforce.
Cleveland Cavaliers has the highest total salary expenditure among all teams.
The Center (C) position accounts for the highest overall salary expenditure.
The correlation analysis indicates a weak positive relationship between age and salary, suggesting that salary tends to increase slightly with age, although age is not a strong predictor of salary.
