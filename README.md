Project on **_Online Course Platform: Student Performance & Engagement Analysis_**

**Analysis Summary: Student Performance & Engagement**

This project analyzes how students engage with online courses and what factors contribute to successful course completion and satisfaction. The analysis focuses on performance patterns, engagement behavior, and demographic impact using both cleaned data and interactive visualizations.

**Core Analysis Objectives:**

**1. Student Engagement Analysis**

Measure how much time students are investing (Time_Spent) and how it correlates with their course progress.

Categorize students by engagement level (Low, Medium, High).

Evaluate session attendance to see how consistent participation affects outcomes.

**2. Performance Evaluation**

Identify high-performing students based on completion status and feedback ratings.

Analyze the relationship between progress % and rating to understand satisfaction vs. effort.

Detect students who completed the course but gave poor ratings, or vice versa.

**3. Demographic Trends**

Understand how age groups (e.g., students, early career professionals) engage differently.

Compare completion rates by country (e.g., India vs. others) to uncover geographic trends.

Analyze gender distribution and its impact on course performance, if any.

**4. Course & Category Performance**

Identify which courses and categories (e.g., Data Science, Business) have the highest completion rates and ratings.

See which courses attract more students but fail to retain them (low progress/high dropout).

**5. Enrollment Trends**

Track how enrollment varies over time—monthly trends may reflect marketing success, seasonal interest, or drop-off patterns.

**6. Feedback Quality**

Analyze distribution of feedback scores (1 to 5).

Identify which courses or instructors consistently receive high or low ratings.

**7. Key Insights Expected:**

a) What defines a high-performing student?

b) Which course categories are most effective or popular?

c) Is there a clear link between time invested and learning outcomes?

d) Do engagement patterns vary across age groups, countries, or gender?

e) What improvements can be made in underperforming courses?

**Process:**

**Excel – Data Cleaning & Preparation**

Normalized inconsistent formats in Name, Email, Time_Spent, and Age

Standardized and cleaned Gender, Country, and Completed fields

Extracted session attendance count from comma-separated date strings

**Created new columns:**

Experience_Level (based on Age)

Engagement_Level (based on Time Spent + Progress)

High Performer flag (Completed + High Feedback)

**Power BI – Interactive Dashboard**

Overview KPIs:  Total students, avg. rating, completion rate, avg. progress

Category Analysis:  Course category performance, completion rate by country, feedback vs. course matrix

Engagement Heatmap:   Visualizing attendance and time spent patterns

Custom DAX Measures:

Completion % by category

Avg. time spent per course

Correlation between progress and rating (scatter plot)

Includes drill-throughs, bookmarks and slicers for dynamic filtering by course, country, and experience level.

**Contents:** 

Microsoft Excel file – Advanced Cleaning Tasks

Power BI file – Advanced Dashboard Tasks

Power BI Dashboard Screenshots

**Tools Used:**  Excel, Power BI, DAX

**Domain:**  E-Learning, EdTech Analytics, Student Behavior Analysis

