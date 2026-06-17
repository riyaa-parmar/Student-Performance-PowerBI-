# 🎓 Student Performance Dashboard

## 📌 Project Overview

The Student Performance Dashboard is an interactive Power BI project developed to analyze student academic performance, attendance records, and behavioral activities. The dashboard provides insights into student achievements, attendance patterns, and classroom behavior through interactive visualizations and reports.

---

## 🎯 Objectives

- Monitor student academic performance.
- Analyze attendance patterns.
- Track student behavior records.
- Identify high, medium, and low-performing students.
- Support data-driven educational decisions.

---

## 📂 Dataset Information

The project uses four datasets:

### Students Table
- StudentID
- Name
- Gender
- Class
- Section

### Scores Table
- StudentID
- Subject
- ExamType
- Score
- MaxScore
- Term

### Attendance Table
- StudentID
- Date
- Status
- Reason

### Behavior Table
- StudentID
- Date
- BehaviorType
- Notes

---

## 🔑 Data Model

### Primary Key
**StudentID** (Students Table)

### Foreign Key
**StudentID** is used as a Foreign Key in:
- Scores Table
- Attendance Table
- Behavior Table

### Relationship Model

Students (1)
│
├── Scores (Many)
├── Attendance (Many)
└── Behavior (Many)

---

## 📊 Dashboard Pages

### 🏠 Overview Dashboard

Features:
- Total Students KPI
- Attendance Percentage KPI
- Average Score KPI
- Behavior Count KPI
- Subject-wise Performance
- Performance Trend by Term
- Behavior Distribution
- Student Performance Table
- Interactive Slicers
- Key Insights

---

### 📊 Academic Analysis

Features:
- Average Score by Class
- Subject-wise Performance Analysis
- Performance by Exam Type
- Performance Category Distribution
- Attendance vs Academic Performance
- Academic Insights

---

### 👤 Student Profile (Drillthrough)

Features:
- Student Information
- Attendance Percentage
- Average Score
- Behavior Count
- Subject-wise Performance
- Behavior Distribution
- Attendance Trend

---

### 🔍 Tooltip Page

Features:
- Student Snapshot
- Attendance Percentage
- Average Score
- Performance Category
- Mini Subject Analysis

---

## ⚡ Dashboard Features

- Data Cleaning using Power Query
- Data Modeling
- DAX Calculations
- KPI Cards
- Slicers & Filters
- Drillthrough Page
- Report Tooltips
- Interactive Navigation
- Data Storytelling

---

## 📖 Key Insights

- Overall attendance remains above 90%.
- Student performance is stable across academic terms.
- Mathematics shows the highest average performance.
- Most students belong to the Medium performance category.
- Higher attendance generally improves academic performance.

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## 📁 Project Structure

```text
Student_Performance_Dashboard/
│
├── 📂 Data
│   ├── Students.xlsx
│   ├── Scores.xlsx
│   ├── Attendance.xlsx
│   └── Behavior.xlsx
│
├── 📂 Dashboard Images
│   ├── Overview.png
│   ├── Academic_Analysis.png
│   ├── Student_Profile.png
│   └── Tooltip.png
│
├── 📂 Images
│
├── 📊 Student Performance Dashboard.pbix
│
└── 📄 README.md
```

---

## 🚀 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Data Modeling
- DAX Functions
- Interactive Dashboard Design
- Drillthrough Analysis
- Report Tooltips
- Business Intelligence Reporting

---

## 👩‍💻 Author

**Riya Parmar**

GitHub:  
https://github.com/riyaa-parmar

⭐ If you find these projects useful, consider **starring the repository**!
