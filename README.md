# Descriptive-Statistics-and-Hypothesis-Testing-in-Excel

## Introduction
This project summarizes key findings and insights from the descriptive statistics, hypothesis testing, and inferential statistical analysis carried out on the employee dataset using Excel functions and the data analysis toolpak.

The dataset contained 35 columns and 1471 rows including the headers describing the employees working at the time. The key columns for this analysis were employee age, monthly income, years at company, department, education level, gender, marital status and performance rating.

---
## Overview of insights gained from the analysis

### Workforce Demographics and Distribution
The company employs 1,470 individuals across three departments: Research & Development (961 employees), Sales (446 employees), and Human Resources (63 employees). The gender distribution shows a male majority, with 882 male employees (60%) and 588 female employees (40%). This gender imbalance is particularly noteworthy from a diversity and inclusion perspective. In addition, when comparing the ages of employees, it was discovered that the average age of employees is 37 years.

### Compensation Patterns 
The average monthly salary across all employees is about $6,503, with a median of $4,919. The substantial difference between the mean and median suggests a right-skewed distribution, indicating that some high-earning employees are pulling the average upward. Also, female employees have a higher average monthly salary ($6,687) compared to male employees ($6,381), which is contrary to typical industry trends.

### Departmental Structure
Research & Development emerges as the largest department, comprising approximately 65% of the workforce. Sales follows with 30% of employees, while Human Resources maintains a lean structure with just 4% of the total workforce.

### Correlation Analysis
A moderate positive correlation (r ≈ 0.50) exists between employee age and salary, indicating that compensation tends to increase with age, likely reflecting the impact of experience and career progression. However, the correlation's strength suggests that other factors, such as performance, education, and role, also significantly influence salary determinations.

---
## Key Insights

### 1.	Workforce Balance
The significant concentration of employees in R&D suggests a technology-focused organization. However, the relatively small HR department might face challenges in effectively supporting such a large workforce.
### 2.	Gender Distribution
While there is a gender imbalance in overall employment, the higher average salary for female employees indicates successful gender pay equity initiatives.
### 3.	Salary Structure
The wide range of $18,990 and a standard deviation of $4,707.96 suggest considerable variation in employee salaries.
### 4.	Career Development
The moderate age-salary correlation suggests a structured career progression system.

 ---
## Hypothesis Tests
To carry out hypothesis tests, the probability value (p-value) was compared to the significance level (α = 0.05).

**Null Hypothesis:** No significant difference or relationship exists between variables

**Alternate Hypothesis:** Significant difference or relationship exists between variables

If p > 0.05, we accept the null hypothesis otherwise we reject it because evidence is not enough to back it.

### A. T-Tests
**1.	Gender Pay Gap Analysis (Two-tailed test)**

**Hypothesis:** The average salary of male employees is significantly different from that of female employees.

**Finding:** The p-value 0.2218 > 0.05 which means the salaries of both male and female employees are fairly the same.

**2.	Employee Tenure and Compensation (One-tailed test)**

**Hypothesis:** "Employees with more than 10 years at the company have a higher average salary"

**Finding:** It was concluded that employees with more than 10 years at the company have a significantly higher average salary than those with 10 years or less. Hence rejecting the null hypothesis since the p-value < 0.05.
     
**3.	Educational Impact on Salary (One tailed test)**

**Hypothesis:** Employees with a master’s degree earn more on average than those with a bachelor’s degree			

**Finding:** Employees with a master’s degree earn less or the same as those with a bachelor’s degree. The p-value 0.1535 > 0.05. Hence, we accept the null hypothesis.
      
**4.	Performance Rating Independence**

**Hypothesis:** “Married Employees have a higher average performance rating than unmarried employees”.

**Finding:** Marital status and performance rating analysis shows minimal variation:
- Unmarried: 3.15 average rating
- Married: 3.16 average rating

The results of p-value > 0.05 suggests that married employees have performance ratings less than or same as unmarried employees (single and divorced combined).

### B. ANOVA Analysis
**1.	Departmental Salary Variations**

A one-way ANOVA was conducted to compare salaries across departments

**Findings:** Results show significant variations:
- Sales: Mean = $6,959
- Research & Development: Mean = $6,281
- Human Resources: Mean = $6,655

The calculated p-value < 0.005. This indicates that department assignment is a significant factor in compensation structure

### C. Chi-Square Tests
**1.	Department and Gender Association**

**Findings:** A chi-square test revealed that there is no relationship between gender and department as p-value calculated > 0.05. This suggests that the distribution of males and females across departments is relatively uniform.
- Sales: 42.4% Female, 57.6% Male
- R&D: 39.4% Female, 60.6% Male
- HR: 31.7% Female, 68.3% Male

**2.	Performance Rating by Years at Company**
Analysis of performance ratings across years of service.

**Null Hypothesis:** The performance rating is independent of the number of years at the company.

**Findings:** The results of p-value > 0.05 suggests that there is no significant relationship between how long an employee has been at the company (grouped into ranges) and performance ratings.

### D. Z-Tests
**1. Male employees in Sales department (One sample proportion)**

**Hypothesis:** The proportion of male employees in the Sales department is greater than 50%

**Finding:** The p-value < 0.05 and the sample proportion (57.62%) is greater than 50%, we reject the null hypothesis. There is sufficient evidence to conclude that the proportion of male employees in the Sales department is significantly greater than 50%. 

**2.	Employees who have spent more than 10 years in the company**
Estimating the proportion of employees who have been at the company for more than 5 years and calculate a 95% confidence interval for this proportion

**Findings:** Approximately 47.21% of employees have been at the company for more than 5 years. We are 95% confident that the true proportion of such employees lies between 44.66% and 49.76%. The margin of error (2.55%) is relatively small, indicating the estimate is reliable.

---
## Inferential Statistics

1. From the analysis, when it comes to the average salary, we are 95% confident that the true mean monthly income for employees falls between $6,262.063 and $6,743.8.
2. In terms of average years at the company, we are 95% confident that the true average tenure of employees at the company lies between 6.69 and 7.32 years.
---
## Conclusion
This analysis provides valuable insights for strategic workforce planning, compensation management, and diversity initiatives. The findings highlight some positive aspects, like potential gender pay equity and the steady salary growth with higher education levels, showing that the company’s policies are making an impact. However, the gender imbalance across the workforce points to areas that could benefit from a closer look to improve diversity.
