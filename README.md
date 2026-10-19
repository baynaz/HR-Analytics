# HR Analytics Dashboard

## 📊 Overview

This project explores **HR analytics and employee attrition** using the IBM HR Analytics dataset.

The objective is to transform raw HR data into actionable insights through data preparation, KPI definition, and interactive visualization.

---

## 🎯 Objectives

The main objectives of this project are to:

- Analyze employee attrition and workforce characteristics
- Calculate key HR performance indicators
- Identify populations with higher attrition rates
- Explore the relationship between working conditions and employee departures
- Build an interactive dashboard for HR reporting and analysis
- Demonstrate a complete BI workflow from raw data to business insights

---

## 🗂️ Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset.

The dataset contains information about **1,470 employees** and includes 35 variables covering different aspects of the employee experience, such as:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Years at Company
- Job Satisfaction
- Work-Life Balance
- Overtime
- Attrition
- Job Level
- Education
- Business Travel

The dataset is publicly available on Kaggle:

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

The data is used for analytical and educational purposes.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Data visualization and dashboarding
- **Power Query** — Data preparation and transformation
- **DAX** — KPI and measure creation
- **CSV** — Source data format

---

## 🔄 Data Workflow

The project follows a simple Business Intelligence workflow:

```text
Raw HR Data
     ↓
Data Quality Checks
     ↓
Data Preparation
     ↓
KPI Definition
     ↓
Data Visualization
     ↓
HR Analysis
     ↓
Business Insights
```

### 1. Data Preparation

The data is imported into Power BI and prepared using Power Query.

The preparation process includes:

- Reviewing data types
- Checking missing values
- Checking potential duplicates
- Reviewing categorical variables
- Preparing variables for analysis
- Ensuring consistency of the dataset

### 2. KPI Definition

The dashboard focuses on several key HR indicators:

| KPI | Description |
|---|---|
| Headcount | Total number of employees |
| Departures | Number of employees who left the company |
| Attrition Rate | Percentage of employees who left |
| Average Monthly Income | Average monthly employee income |

The attrition rate is calculated as:

```text
Attrition Rate =
Number of Departures / Total Headcount
```

---

## 📈 Dashboard

The Power BI dashboard provides an interactive view of employee attrition.

### Main indicators

- Total Headcount
- Number of Departures
- Attrition Rate
- Average Monthly Income

### Main analyses

The dashboard allows attrition to be explored by:

- Department
- Job Role
- Overtime
- Years at Company
- Gender
- Other employee characteristics

Interactive filters can be used to explore specific employee populations.

---

## 🔎 Key Questions

The analysis focuses on questions such as:

### Workforce

- How large is the employee population?
- How is the workforce distributed across departments and roles?

### Attrition

- What is the overall attrition rate?
- Which departments have the highest attrition?
- Which job roles show higher departure rates?
- Does attrition vary according to employee seniority?

### Working Conditions

- Is attrition different for employees working overtime?
- Are there employee populations that require further investigation?

---

## 💡 Business Insights

The dashboard is designed to help identify patterns that may require further investigation.

For example, a higher attrition rate among employees working overtime may indicate a potential relationship between workload and employee retention.

However, observed relationships should not automatically be interpreted as causal relationships. Additional analysis would be required to identify the underlying causes.

Potential areas for further investigation include:

- Workload and overtime
- Employee seniority
- Job role
- Department
- Compensation
- Job satisfaction
- Work-life balance
- Career progression

---

## 🔐 Data Considerations

HR data can contain sensitive and personal information.

In a real-world HR analytics project, particular attention should be paid to:

- Data privacy
- Access control
- Data minimization
- Data quality
- Data governance
- Anonymization or pseudonymization
- Regulatory requirements such as GDPR

The dataset used in this project is a public analytical dataset and does not represent a company's actual employee database.

---

## 🚀 Future Improvements

Possible extensions of this project include:

- Creating an HR data model with separate fact and dimension tables
- Adding additional HR KPIs
- Implementing employee tenure categories
- Adding salary analysis
- Developing time-based HR indicators
- Building a data quality monitoring layer
- Adding predictive analytics for employee attrition
- Exploring employee segmentation
- Connecting the dashboard to a database instead of a static CSV file

---

## 📁 Project Structure

```text
hr-analytics/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── powerbi/
│   └── HR_Analytics.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```
