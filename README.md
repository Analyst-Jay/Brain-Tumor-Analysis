# Brain Tumor Analysis | Power BI

## Project Overview

This project presents an interactive Power BI dashboard for exploring brain tumor patient data. It focuses on patient demographics, tumor characteristics, symptoms, affected brain regions, treatment profiles, and diagnosis trends.

The analysis uses two datasets: `Brain Tumor Data.csv`, containing 10,000 patient records and 12 columns, and `Tumor Images.csv`, containing image references for the tumor grades.

The dashboard is organised into three pages: **Patient Overview**, **Tumor Analysis**, and **Insights and Recommendation**.

## Project Objectives

- Analyse the demographic distribution of patients.
- Explore tumor types, grades, and sizes.
- Examine symptoms and affected brain regions.
- Analyse treatment types, laterality, and histology confirmation.
- Explore diagnosis trends from 2015 to 2025.
- Present the analysis through interactive visuals and summary metrics.
- Communicate findings and recommendations based on the dataset.

## Tools and Technologies

- **Microsoft Power BI** — dashboard development and visualisation
- **Power Query** — data preparation and transformation
- **DAX** — measures and KPI calculations
- **CSV datasets** — source data

## Dashboard Pages

### 1. Patient Overview

The Patient Overview page provides a summary of the dataset and its major patient-level patterns.

It includes:

- KPI cards for patient count, average tumor size, average age, and histology confirmation rate
- Yearly diagnosis trend by patient count
- Treatment type distribution
- Gender distribution
- Tumor grade by age group
- Age group distribution
- Tumor grade image references

The page uses the following age groups:

| Age Group | Age Range |
|---|---:|
| Children | 0–14 |
| Young Adults | 15–39 |
| Middle-aged Adults | 40–64 |
| Older Adults | 65+ |

The diagnosis trend examines distinct patient counts by diagnosis year across the 2015–2025 period.

### 2. Tumor Analysis

The Tumor Analysis page focuses on the characteristics and distribution of tumors recorded in the dataset.

The analysis explores:

- Tumor type and tumor grade
- Tumor size patterns
- Tumor characteristics across age groups
- Affected brain regions
- Symptoms recorded for patients
- Laterality and other available tumor-related fields

These views support comparisons across the available tumor and patient attributes.

### 3. Insights and Recommendation

This page presents the key observations drawn from the analysis and translates them into recommendations for further exploration.

It brings attention to patterns in the patient profile, tumor characteristics, diagnosis trends, and treatment distribution.

The observations are descriptive of the supplied dataset and should not be interpreted as medical conclusions.

## Key Performance Indicators

The dashboard includes the following measures:

| KPI | Description |
|---|---|
| Patient Count | Number of patients represented in the current filter context |
| Average Tumor Size | Mean recorded tumor size in centimetres |
| Average Age | Mean age of patients in the current filter context |
| Histology Confirmation Rate | Share of patient records with histology confirmation |

The KPI values respond to the dashboard's filters and selections. As a result, values displayed under a filter may differ from the overall dataset totals.

## Data Analysis Workflow

1. Inspected the source datasets and their fields.
2. Prepared the data for analysis and visualisation.
3. Created age groups to support demographic comparisons.
4. Developed measures for patient count, average age, average tumor size, and histology confirmation.
5. Analysed diagnosis trends using diagnosis dates.
6. Built interactive dashboard pages to explore patient and tumor characteristics.
7. Summarised the observations in an insights and recommendation page.

## Important Note

This project is an educational and exploratory analysis of the provided dataset. It does not provide medical diagnosis, treatment advice, or clinical recommendations. Findings are limited to the data available in the source files.

## Conclusion

The Brain Tumor Analysis project demonstrates the use of Power BI to organise and explore healthcare-related data through interactive visualisations.

By examining patient demographics, tumor characteristics, symptoms, affected brain regions, treatment profiles, and diagnosis trends, the dashboard provides a structured overview of the dataset and communicates its observed patterns.

---

**Project Category:** Data Analytics  
**Project Focus:** Healthcare Data Analysis and Dashboarding  
**Tool:** Microsoft Power BI  
**Dataset:** Brain Tumor Data and Tumor Images
