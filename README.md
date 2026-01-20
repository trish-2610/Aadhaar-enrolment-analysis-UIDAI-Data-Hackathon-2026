# Unlocking Societal Trends in Aadhaar Enrolment and Updates
### District-wise Analysis of Madhya Pradesh

## Overview

Aadhaar enrolment plays a critical role in access to government services, welfare delivery, and digital inclusion.
This project analyzes district-level Aadhaar enrolment data for **Madhya Pradesh** to uncover clear patterns, gaps, and imbalances across regions, age groups, and time.

The goal is to convert raw enrolment data into **simple, actionable insights** that can support better planning and targeted government interventions.

---

## Problem Statement

Although Aadhaar coverage is widespread, enrolment activity is not evenly distributed.
Some districts show very high enrolment activity while others lag behind.

Understanding these differences is important for:

* Improving outreach strategies
* Planning enrolment infrastructure
* Ensuring inclusive and balanced coverage

---

## Key Objectives

* Study how Aadhaar enrolments are distributed across districts
* Identify districts with the highest and lowest enrolment activity
* Analyze enrolments across different age groups
* Understand how enrolment activity changes over time

---

## Dataset Used

**UIDAI Aadhaar Enrolment Dataset**

**Scope**

* State: Madhya Pradesh
* Level: District-wise
* Time: Date-wise enrolment records

**Key Columns**

* `district` – District name
* `date` – Date of enrolment activity
* `age_group_0_to_5` – Enrolments for ages 0–5
* `age_group_5_to_17` – Enrolments for ages 5–17
* `age_group_18_plus` – Adult enrolments
* `total_enrolments` – Total enrolments per record

---

## Methodology

* Loaded and reviewed raw UIDAI data
* Cleaned and standardized columns
* Removed irrelevant fields
* Created total enrolment metrics
* Aggregated data at district and state levels
* Performed univariate, bivariate, and trivariate analysis
* Built clear static and interactive visualizations
* Generated insights and policy-oriented recommendations

---

## Data Analysis Approach

### Univariate Analysis

* Distribution of total enrolments across districts
* Age-group wise enrolment contribution

### Bivariate Analysis

* District vs enrolments comparison
* Time-based enrolment trends

### Trivariate Analysis

* District-wise age-group patterns over time
* Identification of unusual or inconsistent enrolment behavior

---

## Key Insights

* Aadhaar enrolment is **highly concentrated in a few districts**, with Indore leading by a large margin
* Most districts fall in low-to-medium enrolment ranges
* Enrolment activity is **dominated by the 0–5 age group**
* Adult enrolments remain consistently low across districts
* Enrolment trends show **sharp spikes**, indicating drive-based rather than continuous activity

---

## Tools and Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Plotly for interactive visualizations
* Jupyter Notebook

---

## Repository Structure

```
project/
│
├── data/
│   ├── aadhaar_dataset.csv
│   ├── aadhaar_cleaned_dataset.csv
│   ├── aadhaar_state_level_summary.csv
│   └── aadhaar_district_level_summary.csv
│
├── notebooks/
│   ├── Data_Cleaning_and_Preprocessing.ipynb
│   └── Data_Analysis_and_Visualizations.ipynb
│
├── requirements.txt
└── README.md
```

---

## Future Scope

* Build ML models to predict enrolment demand by district
* Use clustering to group districts with similar enrolment behavior
* Apply anomaly detection for early identification of irregular trends
* Integrate GenAI for automated insight generation and reporting

---

## Submission Details

**Submitted by**
Trishansh Sahane
Data Hackathon Participant

**Code Repository**
All code and datasets used in this project are available in this repository for transparency and reproducibility.

---

This project is designed to support **data-driven governance**, enabling focused outreach, efficient resource allocation, and inclusive Aadhaar coverage across Madhya Pradesh.
