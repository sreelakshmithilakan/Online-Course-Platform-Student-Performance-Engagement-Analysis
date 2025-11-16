# 📚 Online Course Platform: Student Performance & Engagement Analysis  
### Power BI Dashboard & Excel Data Preparation

---

## Analysis Summary
This project explores how students engage with online courses and identifies the factors that contribute to successful course completion and satisfaction. It highlights performance patterns, engagement behavior, and demographic influences using cleaned datasets and interactive Power BI visualizations.

---

## 🎓 Core Analysis Objectives

### 1️. Student Engagement Analysis
- Measure time invested (Time_Spent) and its correlation with course progress  
- Categorize students by engagement level (Low / Medium / High)  
- Evaluate session attendance to understand consistency in learning  

### 2️. Performance Evaluation
- Identify high-performing students (Completion Status + High Ratings)  
- Analyze progress % vs. rating to understand satisfaction vs effort  
- Detect inconsistencies (e.g., completed course but low rating)  

### 3️. Demographic Insights
- Analyze engagement trends across age groups  
- Compare completion rates across countries  
- Evaluate gender distribution and performance impact  

### 4️. Course & Category Performance
- Identify top-performing course categories  
- Detect courses with high enrollment but low retention  
- Compare instructor and course-level ratings  

### 5️. Enrollment Trends
- Track month-wise enrollment patterns  
- Identify seasonal variations and marketing impact  

### 6️. Feedback Quality
- Analyze feedback score distribution (1–5)  
- Identify consistently high- or low-rated courses/instructors  

---

## 💡 Key Questions Answered
- What defines a high-performing student?  
- Which course categories drive the highest success and satisfaction?  
- Is there a strong link between time invested and outcomes?  
- How does engagement vary across age, country, or gender?  
- What improvements can enhance underperforming courses?  

---

## 🧹 Process Overview

### 📘 Excel – Data Cleaning & Preparation
- Normalized Name, Email, Age, Time_Spent  
- Cleaned Country, Gender, Completed fields  
- Extracted attendance count from comma-separated date strings  

**Created Columns:**
- `Experience_Level`  
- `Engagement_Level`  
- `High_Performer` flag  

---

### 📊 Power BI – Interactive Dashboard
**Includes:**  
- KPI Cards (Total Students, Avg Rating, Completion Rate, Progress)  
- Category & Country performance visuals  
- Engagement heatmap (attendance + time spent)  
- Feedback distribution analysis  
- Dynamic slicers & drill-through pages  

**Custom DAX Measures:**  
- Completion % by Category  
- Avg Time Spent per Course  
- Progress–Rating Correlation  

---

## 📁 Contents
- 📘 Excel File – Cleaned dataset & transformations  
- 📊 PBIX File – Interactive Power BI dashboard  
- 🖼️ Dashboard Screenshots  

---

## 🛠️ Tools Used
- **Excel**  
- **Power BI**  
- **DAX**  

---

## 🌐 Domain
**E-Learning · EdTech Analytics · Student Behavior Analysis**

---
