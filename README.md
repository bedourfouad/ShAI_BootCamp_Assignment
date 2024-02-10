# ShAI_BootCamp_Assignment

## About Dataset
The salaries dataset provides information about the employees of an organization, including details such as salary, job titles, departments, and additional information like experience, education, and employment history.

## Features
- 'Id'
- 'EmployeeName'
- 'JobTitle'
- 'BasePay'
- 'OvertimePay'
- 'OtherPay'
- 'Benefits'
- 'TotalPay' (salary)
- 'TotalPayBenefits'
- 'Year'
- 'Notes'
- 'Agency'
- 'Status'

## Tasks

### 1. Basic Data Exploration
- Identify the number of rows and columns in the dataset.
- Determine the data types of each column.
- Check for missing values in each column.

### 2. Descriptive Statistics
- Calculate basic statistics: mean, median, mode, minimum, and maximum salary.
- Determine the range of salaries.
- Find the standard deviation.

### 3. Data Cleaning
- Handle missing data using a suitable method. Explain why you chose the method.

### 4. Basic Data Visualization
- Create histograms or bar charts to visualize the salary distribution.
- Use pie charts to represent the proportion of employees in different departments.

### 5. Grouped Analysis
- Group the data by one or more columns.
- Calculate summary statistics for each group.
- Compare average salaries across different groups.

### 6. Simple Correlation Analysis
- Identify any correlation between salary and another numerical column.
- Plot a scatter plot to visualize the relationship.

### 7. Summary of Insights
Insights:
1. **Job Title Variations:**
   The dataset exhibits numerous variations in job titles, including typos, different cases, and abbreviations. Establishing predefined categories during data collection could enhance consistency in job titles.

2. **Departments with the Highest Average Salary:**
   Fire Department and Legal Department showcase the highest average salary, closely followed by the Administrative Department.

3. **TotalPay Mode and Zero Values:**
   The mode of the 'TotalPay' column is 0, indicating a significant number of entries with no recorded salary. Further analysis is required to comprehend and address the presence of zero values, which may signify instances where no salary information is provided for certain job titles.

4. **Redundant Column:**
   The 'Agency' column contains only one unique value, rendering it redundant. It might be beneficial to consider removing or consolidating this column to simplify the dataset.
