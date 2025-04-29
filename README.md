# patient-treatment-analysis
# Patient Treatment Propensity Analysis

## Overview
This project analyzes semen analysis data from 408 patients collected by Kindbody in 2021 to understand the **propensity of patients to seek fertility treatment** based on their semen parameters. It investigates whether biological factors like sperm count, movement, and shape influence patients' decisions to pursue fertility treatment.

## Objectives
- Compare **Total Motile Count (TMC)** and **sperm diagnosis results** to each patient's treatment status.
- Identify patterns between semen parameters and patients who sought treatment versus those who did not.
- Provide insights to improve patient education and support in fertility clinics.

## How It Works
1. **Data Collection**: The dataset included semen parameters such as TMC, sperm concentration, motility, and morphology for 408 patients.
2. **Categorization**:
   - Patients were classified into normal or abnormal categories based on clinical thresholds.
   - TMC was divided into bins related to the likelihood of natural conception (e.g., Natural, IUI, IVF, Azoospermia).
3. **Analysis**:
   - Treatment acceptance was compared across different sperm diagnoses.
   - Relationships between TMC levels, sperm abnormalities, and conversion status were analyzed.

## Key Findings
- **75% of patients** had a TMC high enough for potential natural conception, yet many had abnormalities in sperm morphology.
- **Teratospermia** (abnormal sperm shape) was the most common abnormality.
- Patients with **very low sperm counts** (e.g., Azoospermia, Oligospermia) were more likely to seek treatment.
- Around **two-thirds of patients** with movement or shape abnormalities (Astheno and Terato groups) did not pursue recommended treatments.

## Why It Matters
While many patients have sperm counts sufficient for natural conception, overlooked issues like sperm morphology can significantly impact fertility outcomes. This study shows the importance of educating patients beyond just sperm count numbers to support informed treatment decisions.

## Tools Used
- **Excel**: Data cleaning, pivot tables, summary statistics.
- **Data Analysis Toolkit**: Statistical testing.
- **Graphing Tools**: Bar charts and breakdowns of patient populations.

## How to Use This Repository
- View the report for insights into patient treatment behavior.
- Use the analysis structure as a model for similar healthcare data projects.

## Future Improvements
- Implement predictive modeling to forecast likelihood of treatment acceptance based on patient parameters.
- Use Python (pandas, matplotlib) to automate and enhance the analysis and visualizations.
- Expand the study with multi-year patient datasets for trend analysis.

---

**Author**: Jason Agyemang  
**Date**: August 2022
