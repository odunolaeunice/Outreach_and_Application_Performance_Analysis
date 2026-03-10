#Outreach & Application Performance Analysis (Excel & Power BI) 

### Project Overview
This project analyses a comprehensive dataset of 7,543 student applications to DePaul University spanning 95 countries. The goal was to clean a highly disorganised raw dataset, establish proper data governance, and build an interactive Power BI dashboard to help the admissions team track enrollment trends, geographic demographics, and application statuses

### Tools
* Microsoft Excel: Data Cleaning, Exploratory Data Analysis (EDA), and Data Documentation.
* Microsoft Power BI: Interactive Dashboard Design.

### Phase 1: Data Governance & Cleaning (Excel)
Real-world data is rarely clean. The raw dataset contained 80 columns and had an initial Data Quality Score of 38.4%. Before building any visualisations, I conducted a rigorous ETL and documentation process in Excel:
What I Did

- Data Dictionary Creation: Documented all variables to establish a clear tracking standard for the dataset
- Missing Value Treatment: Identified and removed 38 columns with 100% missing data (e.g., Major, I_901_Status)
- Duplicate Analysis: Investigated 2,543 duplicate records, determining they were intentional tracking artifacts for different application stages rather than entry errors
- Standardisation: Cleaned geographic data (India accounting for 61.2% of records) and formatted date columns for time-series analysis

*(Note: The full Data Quality Report and Data Dictionary are available in the Excel documentation file in this repository).*

### Phase 2: Visual Analytics (Power BI)
With a clean dataset of 4,999 unique students, I imported the data into Power BI to build an interactive admissions dashboard. 

*Key Features & Insights:*
1. Geographic Footprint: Visualized the dominance of the Indian market while identifying secondary growth regions among the other 94 countries represented.
2. Program Popularity: Tracked the most selected degree types and first-choice colleges (e.g., Jarvis College of Computing and Digital Media).
3. Application Tracking: Created dynamic filters to allow stakeholders to drill down by Intake Year, Term, and Admission Status.

## Recommendations
- Implement early document checklist to prevent 580+ applications stalling
- Diversify geographic outreach as 61% India concentration creates risk; target secondary markets in other represented countries
- Focus counsellor capacity, single counsellor handling majority of outreach is unsustainable at scale
- Prioritise Fall intake campaigns,        Fall accounts for 72% of all applications; Q2/Q3 outreach should be maximised

 **Author:** Odunola Adams


