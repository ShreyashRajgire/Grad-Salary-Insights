# Recent-Grads-Salary-Analysis

This repository contains a comprehensive analysis of recent graduate salaries in the United States, leveraging data . The analysis aims to uncover insights into the factors influencing salary variations, with a particular focus on major category, gender representation, and popularity of different majors.

## Motivation

Understanding the relationship between educational choices and earning potential is crucial for both students and policymakers. This analysis provides valuable insights into salary trends across various majors, empowering students to make informed decisions about their educational paths and highlighting potential areas for intervention to address salary disparities.

## Dataset

The analysis utilizes the `recent-grads.csv` dataset. This dataset contains information on recent graduates from various colleges and universities in the United States, including details about their majors, salaries, employment rates, and demographic characteristics.

## Analysis

The analysis explores several key questions:

* **Which major categories have the highest and lowest median salaries?**
* **How does the share of women in a major relate to its median salary?**
* **Are the most popular majors also the highest paying?**
* **How does gender representation vary across different majors?**

To answer these questions, the analysis employs various statistical and visualization techniques, including:

* **Descriptive Statistics:** Calculation of median salaries, share of women, and total graduates for each major category.
* **Data Visualization:** Creation of box plots, bar graphs, and scatter plots to visually represent salary distributions and relationships between variables.
* **Regression Analysis:** Building a regression model to examine the impact of the share of women on median salary.

## Key Findings

* **Engineering majors consistently rank among the highest earners, while education and arts majors tend to have lower median salaries.**
* **There is a statistically significant negative correlation between the share of women in a major and its median salary.**
* **The most popular majors, such as business and psychology, do not necessarily command the highest salaries.**
* **Gender disparities are evident in certain major categories, with engineering and computer science dominated by men, while education and health professions have a higher proportion of women.**


## Visualizations

The analysis includes several visualizations to illustrate these findings:

**1. Box Plot of Median Salaries by Major Category:**

![image](https://github.com/user-attachments/assets/c98f43d1-5049-437f-822e-c0c93807239b)

*This visualization provides a clear overview of the distribution of median salaries across different major categories.*

**2. Bar Graph of Median Salaries by Major Category:**

![image](https://github.com/user-attachments/assets/2d6f5ac8-ad35-47db-bf6a-f62814e04107)

*This bar graph ranks major categories based on their median salaries, highlighting the highest and lowest earning categories.*

**3. Scatter Plots of Highest and Lowest Earning Majors:**

![image](https://github.com/user-attachments/assets/5a8363d7-3dab-4e64-8c7a-6608602ae584)

![image](https://github.com/user-attachments/assets/a86dfc79-2447-4dcc-8649-00fb3bef3ef8)

*These scatter plots offer a more granular view of the highest and lowest earning majors within each category.*

**4. Bar Graph of Most Common Major Categories:**

![image](https://github.com/user-attachments/assets/4ba4093e-e597-456d-aea3-b1005e3a2f20)

*This bar graph visualizes the popularity of different major categories based on the total number of graduates.*

**5. Bar Graph of Most Common Majors:**

![image](https://github.com/user-attachments/assets/b9a18af9-2e06-4ac4-a462-89dc5ef93a21)

*This bar graph highlights the most frequently chosen majors among recent graduates.*

**6. Stacked Bar Graph of Gender Distribution by Major:**

![image](https://github.com/user-attachments/assets/913cae0a-480c-489a-ac62-7fc362a3579b)

*This stacked bar graph compares the number of men and women in the top 20 most common majors, illustrating gender representation.*

**7. Scatter Plots of Median Salary vs. Share of Women:**

![image](https://github.com/user-attachments/assets/c62f8634-b084-42e4-9eb0-1b8f1b62baff)

*These scatter plots explore the relationship between median salary and the proportion of women in a major category and individual majors.*

**8. Regression model of sharewomen on the salary:**
![image](https://github.com/user-attachments/assets/b8bbf2ef-9b2d-4e0f-8243-4559441f79f0)

## Code

The analysis was conducted using R and the following packages:

* ggplot2
* tidyverse
* plotly

The code for the analysis can be found in the `Majors.Rmd` file.

