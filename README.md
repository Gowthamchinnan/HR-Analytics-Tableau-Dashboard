# HR Analytics Dashboard - Tableau

## Project Overview

This project is an interactive **HR Analytics Dashboard** developed using Tableau to analyze employee attrition, workforce distribution, job satisfaction, age groups, gender, education field, and department-level HR trends.

The dataset contains **1,470 employee records** and the dashboard turns the raw HR data into clear, interactive insights for workforce and attrition analysis.

## Dashboard Preview

![HR Analytics Dashboard](Screenshots/HR%20Dashboard.png)

## Key KPIs

- **Employee Count:** 1,470
- **Attrition Count:** 237
- **Attrition Rate:** 16.12%
- **Active Employees:** 1,233
- **Average Age:** 37

## Dashboard Analysis

The dashboard includes:

- **Department-wise Attrition** – compares attrition across HR, R&D, and Sales.
- **Attrition Count by Gender** – compares male and female attrition counts.
- **Education Field-wise Attrition** – analyzes attrition by employee education background.
- **Employee Count by Age Group** – shows workforce distribution using age bins.
- **Job Satisfaction Rating** – compares employee counts by job role and satisfaction rating.
- **Attrition Rate by Gender for Different Age Groups** – analyzes attrition patterns across age ranges and gender.
- **Education Filter** – allows users to interactively filter the dashboard.

## Calculated Fields

### Attrition Count

```text
IF [Attrition] = "Yes" THEN 1
ELSE 0
END
```

### Attrition Rate

```text
SUM([Attrition Count]) / SUM([Employee Count])
```

### Active Employees

```text
SUM([Employee Count]) - SUM([Attrition Count])
```

## Tableau Features Used

- KPI Cards
- Calculated Fields
- Filters
- Dashboard Actions
- Age Bins
- Bar Charts
- Pie / Donut Charts
- Highlight / Heatmap-style Table
- Labels and Tooltips
- Interactive Dashboard Filtering
- Custom Dashboard Layout and Background

## Dataset

The Excel dataset contains **1,470 employee records** with fields such as:

- Attrition
- Business Travel
- Department
- Education Field
- Employee Number
- Gender
- Job Role
- Marital Status
- Age
- Employee Count
- Job Satisfaction
- Monthly Income
- Performance Rating
- Work Life Balance
- Years at Company
- Years in Current Role
- Years Since Last Promotion

## Project Structure

```text
HR-Analytics-Tableau-Dashboard/
├── README.md
├── Data/
│   └── HR Raw Data.xlsx
├── Tableau/
│   └── HR Data Dashboard Gowtham C.twbx
└── Screenshots/
    └── HR Dashboard.png
```

## Project Objective

The objective of this project is to demonstrate practical HR analytics using Tableau and present employee information through an interactive business intelligence dashboard.

This project demonstrates skills in:

- Data Analysis
- Tableau Dashboard Development
- Calculated Fields
- Data Visualization
- HR Analytics
- Interactive Reporting
- Dashboard Design
- Business Intelligence

## Author

**Gowtham C**
