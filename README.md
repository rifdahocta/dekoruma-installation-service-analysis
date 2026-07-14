# Dekoruma Installation Service Analysis

## Project Overview
This project analyzes the performance of Dekoruma's furniture installation service using Exploratory Data Analysis (EDA) and Statistical Analysis. The objective is to evaluate installation performance and identify whether operational factors are associated with installation failures.

## Dataset
The dataset consists of approximately **300,000 furniture transactions** and includes information about:

- Orders
- Stores & Sales Channels
- Products
- Installation Status
- Delivery Date
- Installation Date
- Assembly Fee

After the ETL process, **294,521** valid transactions remained for analysis.

## Project Workflow

1. Data Cleaning (ETL)
2. Exploratory Data Analysis (EDA)
3. Statistical Analysis
4. Business Insight & Recommendation

## Analysis Performed

### Exploratory Data Analysis
- Dataset Overview
- Transaction Characteristics
- Installation Performance
- Failure Pattern Analysis
- Operational Characteristics

### Statistical Analysis
- Mann–Whitney U Test
  - Delivery Days
  - Installation Days
  - Assembly Fee

## Key Findings

- Installation Success Rate: **79.58%**
- Installation Failure Rate: **20.42%**
- Failure rates across product categories, sales channels, and stores are relatively similar.
- Statistical analysis indicates that: Delivery duration, installation duration, and assembly fee **do not differ significantly** between successful and failed installations.

These findings suggest that installation failures may be influenced by factors that are not captured in the available dataset.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Looker Studio

## Dashboard

Interactive dashboard is available in Looker Studio:
https://datastudio.google.com/reporting/2a724ac3-78f7-4a70-a123-c601419cb7ab

## Author

**Rifdah Octa**
