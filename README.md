# 📊 Employee Leave / Attrition Dashboard

![Dashboard Preview](image/employee.png)

## 📌 Overview

The **Employee Leave / Attrition Dashboard** is an interactive Power BI project that analyzes employee attrition using HR data. It provides insights into workforce demographics, employee retention, and the key factors influencing employees leaving the organization.

---

## 🎯 Dashboard Highlights

### 📌 Key KPIs
- 👥 Total Employees
- 🚶 Left Employees
- ✅ Stayed Employees
- 🎂 Average Employee Age
- 💼 Average Experience
- 🪑 Benched Employee Percentage

### 📊 Interactive Visualizations
- Attrition Distribution
- Gender-wise Attrition Analysis
- Education-wise Attrition Analysis
- City-wise Attrition Analysis
- Payment Tier Analysis
- Joining Year Trend
- Employee Retention Trend

### 🎛️ Dashboard Filters
- Education
- Joining Year
- City
- Payment Tier
- Gender
- Ever Benched

---

## 📂 Project Structure

```text
Employee-Leave-Attrition-Dashboard/
│
├── data/
│   └── employee.csv
│
├── image/
│   └── employee.png
│
├── PowerBI_dashboard/
│   └── employee.pbix
│
└── README.md
```

---

## 📋 Dataset Columns

| Column | Description |
|---------|-------------|
| Education | Employee education level |
| JoiningYear | Employee joining year |
| City | Employee work location |
| PaymentTier | Salary tier (1 = Low, 2 = Medium, 3 = High) |
| Age | Employee age |
| Gender | Male/Female |
| EverBenched | Whether the employee was benched (Yes/No) |
| ExperienceInCurrentDomain | Years of experience in the current domain |
| LeaveOrNot | Employee status (0 = Stayed, 1 = Left) |

---

## 💡 Key Insights

- Lower payment tier employees tend to have higher attrition.
- Benched employees are more likely to leave the company.
- Attrition varies across different cities.
- Employee experience has a significant impact on retention.
- Education and gender also influence attrition trends.

---

## 🛠️ Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- CSV Dataset

---

## 🚀 Future Enhancements

- Department-wise analysis
- Machine Learning-based attrition prediction
- Employee performance analysis
- Power BI Service deployment

---

## 👨‍💻 Author

**Arvind Yadav**
