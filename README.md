
# Travel, Food & Beverages: A Case Study on Adverse Event Reporting in the Food and Cosmetics Industry
## Background
This project leverages the CAERS (CFSAN Adverse Event Reporting System) dataset, which is a vital resource for the FDA. The dataset contains adverse event and product complaint reports related to foods, dietary supplements, and cosmetics from 2004 to the second quarter of 2017. Each record is meticulously coded using MedDRA (Medical Dictionary for Regulatory Activities) terminology, ensuring consistent and standardized reporting across various product categories. This case study focuses on understanding the patterns and risks associated with these adverse events to enhance safety surveillance in the food and cosmetics industries.

## Objective
The primary goal of this project is to analyze the CAERS dataset to identify trends, risks, and key factors associated with adverse events related to food, dietary supplements, and cosmetics. The analysis seeks to extract valuable insights into product categories, patient demographics, types of symptoms, and outcomes reported, enabling better safety regulations and risk mitigation strategies for these industries. Insights derived from the analysis will contribute to public health improvements by highlighting potential areas for intervention and risk prevention.

## Data Source
The analysis is based on the CAERS_ASCII_2004_2017Q2.csv file, which contains the following key fields:

**RA_Report #**: Unique identifier for each adverse event report.

**RA_CAERS Created Date**: Date of report entry into the CAERS database.

**AEC_Event Start Date**: Date the adverse event began.

**PRI_Product Role**: Role of the product (suspect or concomitant).

**PRI_Reported Brand/Product Name**: Product name associated with the event.

**PRI_FDA Industry Code & Name**: Industry categorization (e.g., 'Bakery Prod/Dough/Mix/Icing', 'Ice Cream Prod').

**CI_Age at Adverse Event**: Age of the affected individual.

**CI_Age Unit**: Age measurement unit (years, months).

**CI_Gender**: Gender of the affected individual.

**AEC_One Row Outcomes**: Event outcomes (hospitalization, ER visit, etc.).

**SYM_One Row Coded Symptoms**: Coded symptoms related to the event.

## Part I : Data Cleaning, Modeling, and DAX in Power BI
### Data Importing and Preprocessing
The dataset is imported into Power BI for initial exploration and examination.
Data quality issues, including missing values and incorrect data types, are addressed.

### Data Analysis 
**Product Role Categorization**: Categorize products based on their role (suspect or concomitant) to analyze distribution across roles.

**Industry-Based Analysis**: Group data by FDA industry names and examine the distribution of reports within various industries.

**Demographic and Gender Analysis**: Analyze the demographic spread of adverse events based on age and gender.

**Symptom Frequency and Correlation**: Investigate common symptoms and their correlations with patient age, using DAX for advanced calculations.

**Outcome and Industry Relationships**: Analyze the relationship between industry types and adverse event outcomes, categorizing them by severity.

**Time Series Analysis**: Conduct a time-based trend analysis of report submissions.

**Advanced Modeling with DAX**: Develop predictive models for adverse event risks based on age, product type, and symptom severity.

## Part 2: Dashboard Building
#### Adverse Event Reporting Dashboard
The dashboard provides key metrics on report frequency, common symptoms, and product types, with interactive filters for detailed analysis by industry, product role, age group, and gender.
### Demographic Analysis
The dashboard visualizes reporting trends over time and allows users to explore data by age and gender to identify demographic patterns in adverse events.
Correlation and Trend Insights
### Industry and outcome analysis
Interactive visuals illustrate the correlation between industries and reported outcomes, providing insights into potential high-risk categories and trends.

### Data Storytelling and Insights
The dashboard integrates storytelling techniques to summarize key insights derived from the data, helping users quickly identify the most important findings.
Key Features
Comprehensive Data Analysis: Detailed examination of the adverse event data using Power BI, including DAX-driven insights and predictive modeling.
Interactive Dashboard: User-friendly, accessible Power BI dashboard for exploring trends, correlations, and demographics.

## Conclusion
This analysis of adverse event data for the food and cosmetics industries provides essential insights into safety issues and trends. The results of this project are expected to inform future product safety regulations and support the FDA’s goal of improving public health by mitigating potential risks associated with food and cosmetic products.
