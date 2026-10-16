# Banking HR Training Analytics Dashboard

**An HR Analytics project using Power BI and Machine Learning to analyse mandatory employee training, identify pending training, and explore departmental training lapse risks in the banking industry.**

## Project Overview

This project was developed as part of the Business Analytics and AI & Machine Learning module by Group 4.

Using a synthetic dataset of 500 fictional employee records, the project explores how HR analytics and interactive dashboards can help monitor mandatory training completion, analyse training hours, and identify departments requiring follow-up.

The project focuses on Human Resources in the banking and financial services industry, where training in areas such as KYC, AML, cybersecurity, and regulatory compliance is important.

## Business Problem

**Which departments have the highest number of employees with pending mandatory training, and where should HR prioritise follow-up?**

The project aims to provide a clear overview of employee training status, departmental training patterns, and potential training lapse risks.

## Tools and Technologies

* **Power BI:** Interactive dashboards, KPI cards, charts, and department slicers.
* **Python:** Machine learning and data analysis.
* **Pandas and NumPy:** Data manipulation and numerical operations.
* **Scikit-learn:** Data preprocessing, Logistic Regression, and model evaluation.
* **imbalanced-learn:** SMOTENC for handling class imbalance.
* **Microsoft Excel:** Synthetic dataset preparation and organisation.

## Dataset

The project uses 500 fictional employee records prepared for academic purposes.

Key fields include:

* Employee ID
* Department
* Training Status
* Training Hours
* Training Priority

The dataset supports comparisons across departments, training completion status, training hours, and priority levels.

**Note:** The dataset is synthetic and does not contain actual PNB employee records.

## Project Objectives

1. Monitor mandatory training completion and pending training.
2. Identify departments with the largest training backlogs.
3. Compare average training hours across departments.
4. Analyse employee training priorities.
5. Develop an interactive Power BI dashboard for HR reporting.
6. Explore supervised machine learning using Logistic Regression to classify training status.
7. Translate analytical findings into actionable HR recommendations.

## Key Dashboard Insights

The following figures are taken from the project presentation and Power BI dashboard.

| KPI                             |    Result |
| ------------------------------- | --------: |
| Total Employees                 |       500 |
| Average Training Hours          |      13.9 |
| Employees with Pending Training |       215 |
| Overall Pending Training Rate   |       43% |
| High-Priority Employees         | 205 (41%) |

### Department-Level Findings

* **Risk Management:** Highest pending count, with 54 employees.
* **IT & Digital Banking:** Highest pending training share, at approximately 64.2%.
* **Corporate Banking:** 35 employees have pending training.
* **Human Resources:** Highest average training hours, at 15.9 hours.
* **Retail Banking:** Lowest average training hours, at 12.5 hours.
* **Investment Banking:** Lowest pending count among the departments, with 9 employees.

These findings help distinguish departments with the largest backlogs from those with the highest proportion of employees awaiting training.

## Power BI Dashboard Features

The interactive dashboard includes:

* Total employee count.
* Average training hours KPI.
* Pending training KPI.
* Completed versus pending training by department.
* Average training hours by department.
* Training priority distribution.
* Department slicer for interactive filtering.

The department slicer allows users to select an individual department and examine the corresponding metrics and visualisations.

## Machine Learning Approach

The project explores **supervised classification using Logistic Regression** to predict whether an employee's training status is Completed or Pending.

### Workflow

1. Prepare the employee training dataset.
2. Identify input features and the target variable.
3. Preprocess numerical and categorical data.
4. Address class imbalance using SMOTENC, where appropriate.
5. Train a Logistic Regression classifier.
6. Evaluate predictions using suitable classification metrics.
7. Interpret the findings in the context of HR training management.

The presentation also explores departmental training lapse risk bands based on pending-training percentages.

**Important distinction:** Departmental risk bands derived from pending percentages are descriptive classifications, not proof of a validated machine learning prediction. Likewise, specific skill-gap areas are indicative suggestions because the listed dataset fields do not include an explicit skill-gap variable.

## HR Recommendations

Based on the dashboard findings, the following actions are suggested:

* Prioritise training follow-up in Risk Management, IT & Digital Banking, and Corporate Banking.
* Review pending mandatory training across departments.
* Investigate why IT & Digital Banking has the highest pending share.
* Review training-hour differences alongside completion status.
* Use department-level insights to plan reminders and training schedules.
* Validate any machine learning predictions before using them to guide HR decisions.

## Limitations

* The dataset contains fictional employee records.
* Observed associations do not establish causation.
* Training hours alone do not establish training effectiveness or compliance.
* Departmental risk bands depend on the selected thresholds.
* Skill-gap suggestions require validation against actual training-module and employee-skill data.
* Machine learning outputs should be independently evaluated before any real-world application.

## Project Outcome

This project demonstrates how HR data can be transformed into an interactive Power BI dashboard and connected with machine learning concepts to explore employee training patterns.

It combines business problem-solving, data visualisation, and predictive analytics to support more structured and data-informed HR training decisions.

## Academic Context

**Project:** PNB Banking HR – Mandatory Training Dashboard
**Group:** Group 4
**Industry:** Banking and Financial Services
**Function:** Human Resources
**Purpose:** Academic learning and demonstration of Business Analytics, Power BI, and Machine Learning.

---

*Developed as an academic project using synthetic data. This analysis is for educational purposes and does not represent actual PNB workforce information or validated operational predictions.*
