# E-Commerce Sales Analysis

### Project Overview
This data analysis project aims to provide insights into the attrition of a company over the past year. By analyzing various aspects of the attrition data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's attrition.


### Data Sources
Sales Data: The primary dataset used for this analysis is the "Hr data.csv" file, containing detailed information about the attrition made by employee in the company.

### Tools
- Microsoft Excel - Data Cleaning
  
- PowerBI - Data Analysis and Creating reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

- Data loading and inspection.
- Handling missing values.
- Data cleaning and formatting.
  
### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:

- What is the attrition rate in the commpany ?
- Which department has the highest attrition rate and the highest  age band by attrition?
- What department has the hightest job satisfaaction rating?
- what is the attritionn rate by gender for diferent age group ?
  
### Data Analysis
Included some interesting DAX/features  to work with


Active Employee = SUM('HR data'[Employee Count])-SUM('HR data'[Attrition Sum])

Attrition Rate = sum('HR data'[Attrition Sum])/sum('HR data'[Employee Count])

Average age = (SUM('HR data'[Age])/SUM('HR data'[Employee Count]))


### DASHBOARD

![DASHBOARD](https://github.com/Lexies799/HR-Analystics-Dashboard-Power-bi/commit/049e829f41ff7641ad6677208c0c82ed508a95f6)




### Results/Findings
The analysis results are summarized as follows:

The company's attrition rate is 16.12%, with male having the highest attrition rate against the female  and the department of sales Executive having the highest job satisfaction rating.


### Recommendations
Based on the analysis, we recommend the following actions:


- give employee creative freedom
- foster a plesant work enviroment
- offer competitive compensation and salary
- Conduct employee exit interviews to understand why employee leaves and what you can do to improve your retention strategies
