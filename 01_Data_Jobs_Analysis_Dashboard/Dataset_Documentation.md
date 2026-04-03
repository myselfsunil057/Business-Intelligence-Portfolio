---

# 📊 Data Jobs Analysis Dashboard  

---

## 📌 Dataset Overview

This dataset represents a large-scale aggregation of global job postings in the data domain. 
It is designed to analyze hiring trends, salary structures, and skill demand across multiple platforms.

  - **Estimated Records:** 400,000+
  - **Unique Job Listings:** ~113,000
  - **Time Coverage:** Multi-year historical job postings
  - **Geographic Scope:** Global (multi-country dataset)

---

## 📌 Data Sources

The dataset is compiled from multiple job listing platforms, including:
  - LinkedIn
  - Indeed
  - BeBee
  - Other aggregated job portals

> Note: Data is standardized into a unified schema for analytical consistency.

---

## 📊 Key Attributes

| Field Name | Description |
|------------|-------------|
| Job Title | Role designation (e.g., Data Analyst, Data Engineer) |
| Salary | Annual salary converted to USD |
| Location | Country / region of job posting |
| Employment Type | Full-time, Part-time, Contract, Internship |
| Remote Flag | Indicates remote eligibility |
| Source Platform | Origin of job listing |
| Posting Date | Timestamp of job listing |

---

## 🧹 Data Cleaning & Transformation

To ensure analytical accuracy, the following preprocessing steps were applied:
    - Removed non-data-related job categories
    - Standardized job titles into unified role families
    - Converted all salary values to **USD equivalent**
    - Handled missing salary values using **median imputation**
    - Extracted remote work indicators from job descriptions
    - Removed duplicate entries across platforms
    - Normalized location fields into country-level mapping

---

## ⚠️ Assumptions

- Salary values represent **annualized compensation**
- Duplicate postings across platforms are treated as unique if source differs
- Job roles are categorized into standardized analytical clusters
- Missing values are treated using statistical approximation methods

---

## 🎯 Analytical Purpose

The dataset is structured to support:
- Salary benchmarking across roles
- Job demand trend analysis
- Remote vs onsite distribution insights
- Workforce planning intelligence
