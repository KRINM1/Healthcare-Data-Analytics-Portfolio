 Hospital Readmissions Dashboard

Goal
Analyze 30-day hospital readmission performance across U.S. facilities using CMS HRRP (Hospital Readmissions Reduction Program) data for FY 2025.



Tools Used
- Excel (Data cleaning and transformation)
- Power BI (Dashboard visualization)
- GitHub (Version control and portfolio hosting)

Data Source:  
[CMS Hospital Readmissions Reduction Program (HRRP)](https://data.cms.gov/provider-data/dataset/FY_2025_Hospital_Readmissions_Reduction_Program_Hospital)


What I Built
- KPIs
  - Average Excess Readmission Ratio (across all hospitals)
  - Count of Hospitals Above vs. Below National Average (1.0)
  - Total Number of Hospitals Reported  

- Visuals
  - Card visuals for key KPIs  
  - Bar charts for Top 10 and Bottom 10 hospitals by Excess Readmission Ratio  
  - Donut chart showing proportion of hospitals “Above”, “Below”, or “Same” as the national benchmark  
  - Table view of detailed hospital-level data (Facility, Measure, Ratio, National Comparison)

- Data Model
  - Single flat table derived from CMS HRRP dataset
  - Measures created using DAX in Power BI


Key Insights 
- The average Excess Readmission Ratio across hospitals ≈ 0.98, indicating performance near national benchmarks.  
- About 42% of hospitals perform above the national average (>1.0 ratio).  
- Several high-performing facilities maintain *ratios below 0.85, suggesting strong post-discharge programs.  
- Common measures include heart failure, pneumonia, and COPD readmissions.



Next Steps
- Integrate regional grouping (by state or provider type)  
- Compare year-over-year HRRP trends when CMS releases new data  
- Explore predictive modeling for identifying facilities at higher readmission risk

---

Preview
*(Insert Power BI dashboard screenshot here)*

Repo Structure
