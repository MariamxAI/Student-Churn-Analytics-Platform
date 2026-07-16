# Student-Churn-Analytics-Platform
![Python](https://img.shields.io/badge/Python-3.x-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)

A Data Engineering and Analytics project developed to analyze student engagement and identify factors associated with student churn using the Open University Learning Analytics Dataset (OULAD).

---

## Overview

This project demonstrates a complete data engineering workflow, starting from raw educational data and ending with an interactive analytics dashboard.

The pipeline includes data extraction, cleaning, transformation, feature engineering, data warehousing, and visualization to support data-driven academic decision-making.

---

## Project Objectives

- Analyze student learning behavior.
- Identify factors associated with student churn.
- Build an analytics-ready dataset.
- Generate meaningful behavioral features.
- Visualize key insights through an interactive dashboard.

---

## Technology Stack

| Category | Technology |
|-----------|------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Database | PostgreSQL |
| Query Language | SQL |
| Data Visualization | Power BI |

---

## Dataset

**Open University Learning Analytics Dataset (OULAD)**

The dataset contains student demographics, registrations, assessments, courses, and interactions with the Virtual Learning Environment (VLE).

---

## Project Workflow

```text
OULAD Dataset
      │
      ▼
Data Extraction (ETL)
      │
      ▼
Data Cleaning & Validation
      │
      ▼
Feature Engineering
      │
      ▼
PostgreSQL Data Warehouse
      │
      ▼
Power BI Dashboard
```

---

## Repository Structure

```text
student-churn-analytics-platform/
│
├── dashboard/          # Power BI dashboard
├── docs/               # Project documentation
├── images/             # Dashboard screenshots
├── python/             # ETL & Feature Engineering scripts
├── sql/                # SQL scripts and database objects
└── README.md
```

---

## Dashboard Preview

> Dashboard screenshots are available in the **images/** directory.

---

## Key Features

- ETL pipeline for educational data
- Data cleaning and validation
- Feature engineering for student engagement analysis
- PostgreSQL Data Warehouse
- Interactive Power BI dashboard
- Student behavior analytics
## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/student-churn-analytics-platform.git
```

2. Navigate to the project directory.

```bash
cd student-churn-analytics-platform
```

3. Install the required Python packages.

```bash
pip install -r requirements.txt
```

4. Configure the PostgreSQL database and restore the project database if required.

5. Run the ETL and Feature Engineering scripts.

6. Connect the generated database to Power BI to explore the dashboard.

---
## How to Use

- Open the Power BI dashboard.
- Navigate through the available report pages.
- Use filters and slicers to explore student performance and engagement.
- Monitor key performance indicators (KPIs).
- Analyze student behavior and identify potential churn patterns.

## Team

Developed as a collaborative Data Engineering graduation project at - DEPI - AI & Data Science Track.
