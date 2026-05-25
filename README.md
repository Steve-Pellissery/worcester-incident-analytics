# worcester-incident-analytics

## Project Overview

This project analyzes historical public safety incident data from Worcester to understand operational demand patterns across different locations and time periods.

Using Python and Power BI, the project explores how incident activity changes by hour, day, and ZIP code. The analysis was used to identify hotspot areas, high demand operational windows, and possible patrol prioritization opportunities.

The goal of the project was to combine data analysis, forecasting, and business intelligence to support data driven operational planning and operational resource allocation insights.

The dataset used in this project was sourced from the City of Worcester Open Data Portal:

https://opendata.worcesterma.gov/datasets/worcesterma::police-incident-data-2026/about

---

## Tools Used

Python

Pandas

Matplotlib

Scikit learn

Power BI

ChatGPT

GitHub

---

## AI Assisted Development

AI tools such as ChatGPT were used during development to assist with repetitive coding tasks, workflow acceleration, debugging support, and dashboard implementation guidance.

The analytical approach, project direction, interpretation of findings, operational reasoning, and overall decision making were independently performed as part of the project workflow.

---

## Project Workflow

### Data Understanding and Cleaning

The project started with inspecting the raw incident dataset and identifying issues such as:

• Missing ZIP code values stored as blank strings

• Incorrect data types for date and time columns

• Duplicate operational records caused by multiple officers responding to the same incident

The data was cleaned and transformed into an incident level dataset for accurate hotspot and demand analysis.

---

### Exploratory Analysis

Several analyses were performed to understand operational incident patterns, including:

• Incident activity by hour

• Incident activity by weekday

• Most common incident categories

• Geographic hotspot analysis by ZIP code

• Day and hour demand heatmaps

The analysis showed that operational demand consistently increased during afternoon and evening periods, with ZIP codes 1604, 1605, and 1610 showing the highest sustained activity.

---

### Risk Scoring and Operational Prioritization

A risk scoring framework was created using historical incident frequency by ZIP code and hour.

Operational demand windows were categorized into:

• Minimal Demand

• Normal Demand

• Elevated Demand

• Critical Demand

This helped identify the highest priority patrol periods and hotspot regions.

---

### Predictive Modeling

A forecasting model was developed using Random Forest Regression to estimate operational incident demand based on:

• Time of day

• Geographic location

• Weekday patterns

• Seasonal trends

The model demonstrated strong pattern learning capability for operational demand forecasting and temporal hotspot estimation.

---

## Dashboard Pages

### Executive Overview

Summary of incident activity, demand trends, and geographic concentration.

### Geographic Risk Analysis

Heatmaps and hotspot analysis showing high demand ZIP codes and operational intensity by hour.

### Operational Recommendations

Critical demand windows, patrol prioritization insights, and operational resource allocation recommendations.

---

## Key Insights

• Operational incident demand peaked consistently during late afternoon and evening hours.

• ZIP codes 1604, 1605, and 1610 demonstrated the highest sustained operational activity.

• Time of day emerged as the strongest driver of operational demand patterns.

• Critical demand windows were concentrated between 4 PM and 7 PM.

• Geographic hotspot concentration suggested that targeted patrol allocation strategies could improve operational coverage efficiency.

---

## Dashboard Preview

<img width="1352" height="770" alt="image" src="https://github.com/user-attachments/assets/0c13f26f-2de3-458c-af2b-c6766ce94d8d" />
<img width="1344" height="761" alt="image" src="https://github.com/user-attachments/assets/90fd6073-b659-463a-ae63-8ff8d1a9d058" />
<img width="1338" height="760" alt="image" src="https://github.com/user-attachments/assets/d0310c80-e72e-45bb-a12d-6b3389298fb0" />


---

## Author

Steve Pellissery

MS Business Analytics  
Clark University
