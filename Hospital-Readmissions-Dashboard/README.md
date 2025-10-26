# Hospital Readmissions Dashboard

**Goal**  
Analyze 30-day hospital readmission trends and quality metrics using public CMS data.

**Tools Used**  
Power BI (or Oracle Analytics Cloud), Excel, SQL
**Data Source**  
[CMS Hospital Readmissions Reduction Program (HRRP)] https://www.cms.gov/medicare/payment/prospective-payment-systems/acute-inpatient-pps/hospital-readmissions-reduction-program-hrrp
              
**What I Built**  
- KPIs: 30-day readmission rate, LOS, mortality, infection rate  
- Visuals: trend by year, bar chart of top/bottom hospitals, choropleth by state, condition filter (HF/COPD/PNA)  
- Data model: star schema (Admissions, ReadmissionEvents, Providers, Dates)

**Key Insights (placeholder)**  
- Average national readmission rate ≈ 15%  
- [State/Region] shows highest rates; targeted follow-ups reduced readmissions  
- Top hospitals <10% readmission via post-discharge programs

**Next Steps**  
Add predictive modeling using OCI AI (Generative AI + Vector Search).

**Preview**
![Preview](../assets/readmissions_dashboard.png)
