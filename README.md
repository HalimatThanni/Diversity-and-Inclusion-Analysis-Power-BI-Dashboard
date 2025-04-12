# Diversity-and-Inclusion-Analysis-Power-BI-Dashboard

<img width="1000" height="300" alt="images (2)" src="https://github.com/user-attachments/assets/6b2c45e0-2975-4647-832b-7b6869b78102" />

## About the Project

This project presents a comprehensive analysis of Diversity and Inclusion (D&I) within a corporate environment using Power BI. The dataset (not displayed here due to privacy) includes HR-related data focused on gender representation, promotions, performance, hiring trends, and attrition across various job levels.

The dashboard is designed to provide insights to HR executives, diversity officers, and organizational leaders for informed decision-making around inclusion efforts.


## Data Source

The dataset was obtained from PwC Switzerland's online project platform and analyzed in Excel and Power BI. The dataset includes the following key columns:

- Employee ID
- Gender
- Job Level
- Region Group
- Department
- Performance Rating
- Promotion Status (FY21)
- Hiring Status
- Termination Status
- Time in Grade

##  Tools Used

- Power BI Desktop: Data modeling, measures (DAX), and dashboard creation
- Microsoft Excel: Data cleaning and preprocessing
- DAX: Custom measures
- Power BI Visuals: Card, clustered bar chart, line chart, combo chart, slicers, etc.


## Objective

The objective of this project is to analyze and visualize gender-based trends in hiring, promotions, retention, and performance to:

- Assess gender distribution across job levels
- Understand promotion rates for women vs. men
- Evaluate performance metrics in relation to attrition
- Identify gaps in representation and advancement


##   Data Cleaning & Preparation

In the step, what I did was handle missing values, checked for duplicates and any spelling errors in Excel, then imported the cleaned dataset into Power BI. In Power BI, I created multiple measures that will aid my visuals load a bit faster and give more understanding of the data. The measures created are: # of Leavers, # of Men / # of Women, % of Hired Women / % of Hired Men, % of Promoters Who Were Women/Men, % of Employees Promoted (FY21), Avg Performance Rating (Leavers vs Non-Leavers), and Turnover Rate.

## Exploratory Data Analysis (EDA)
Using Power BI, I analyzed key gender-diversity metrics:



1. Hiring Statistics
Executive and Director roles were predominantly filled by men (86–88%).

Entry-level roles like Junior Officer had more balanced or female-leaning hires.

2. Promotions
52.1% of all promotions in FY21 were awarded to women.

Women were promoted more at the Junior Officer and Senior Officer levels.

3. Hired Women
The percentage of hired women increased progressively from Executive to Junior roles.

Junior Officer roles had the highest number and percentage of female hires (47%).

4. Attrition & Turnover
47 employees left the company during FY21.

Turnover rate among men was higher (59%) than among women (41%).

Women showed a slightly higher average performance rating before exit compared to men.

5. Performance Ratings
The difference in performance between leavers and stayers:

Female employees: 0.11-point drop when leaving

Male employees: 0.09-point drop when leaving

6. Time in Grade Before Promotion
Women generally spent more time in grade before getting promoted.

Junior Officers had a promotion cycle averaging ~3.2 years.

## Results & Key Findings

🔹 Leadership roles remain male-dominated, especially at the Executive and Director levels.
🔹 Women receive more promotions than men overall, but mainly in junior roles.
🔹 Attrition among women is lower, potentially signaling greater retention efforts or stronger inclusion at lower levels.
🔹 There’s a performance dip trend before leaving, especially for women.
🔹 The organization is making efforts toward gender inclusion at lower levels but may need to focus on senior-level diversity.


## Recommendations

1. Boost Female Leadership Representation: Implement mentorship and development programs targeting high-potential women for senior roles.
2. Monitor Turnover Patterns: Conduct exit interviews, especially with high-performing women, to understand exit causes.
3. Review Promotion Timing: Standardize promotion cycles and review criteria to eliminate unconscious bias.
4. Integrate Intersectionality: If available, include other diversity factors like age, race, or disability in future analyses.
5. Continuous Tracking: Use this dashboard as a living tool for quarterly or annual D&I audits.

