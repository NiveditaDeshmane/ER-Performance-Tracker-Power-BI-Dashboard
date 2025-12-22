# ER-Performance-Tracker-Power-BI-Dashboard
An interactive Power BI dashboard for monitoring emergency room performance, including patient volume, wait times, admissions, referrals, and satisfaction metrics across monthly and consolidated views.
# ER Performance Tracker | Power BI Dashboard

## Project Overview
---

## Business Objectives
- Monitor ER performance using key operational metrics  
- Analyze patient wait times and service efficiency  
- Understand patient demographics and visit patterns  
- Identify peak hours, high-load days, and referral trends  
- Support better staffing and resource allocation decisions  

---

## Key KPIs
- **Total Number of Patients**
- **Average Wait Time (Minutes)**
- **Patient Satisfaction Score**
- **Number of Patients Referred**
- **Admission vs Not Admitted Patients**
- **% of Patients Treated Within Target Time (30 Minutes)**

---

## Dashboard Views
### 1. Consolidated View
- Overall ER performance across the selected date range
- High-level KPI tracking
- Long-term trends and summary insights

### 2. Monthly View
- Month-wise performance analysis
- Daily patient trends
- Hourly patient distribution

### 3. Patient Details View
- Demographic analysis
- Department and referral insights

---

## Data Analysis & Visualizations
- **Patient Admission Status** (Admitted vs Not Admitted)
- **Patients by Age Group**
- **Patients by Gender**
- **Patients by Race**
- **Patients by Department Referral**
- **Patients by Day and Hour Heatmap**
- **Monthly and Daily Trend Analysis**

---

## Data Model (Conceptual)
The data model is structured around a **fact table** and multiple **dimension tables**:

### Fact Table
- Patient Visits  
  - Visit Date  
  - Wait Time  
  - Admission Status  
  - Referral Indicator  
  - Satisfaction Score  

### Dimension Tables
- Date (Year, Month, Day)
- Patient Demographics (Age Group, Gender, Race)
- Department
- Time (Hour of Visit)

Relationships are built using **star schema design** to ensure optimized performance and accurate aggregations.

---

## Key Insights
- A significant portion of patients are treated **within the target wait time**, but improvement opportunities exist during peak hours.
- Certain **days and time slots** experience consistently higher patient volume.
- Admission rates are nearly balanced, indicating effective triage processes.
- Specific departments account for a majority of referrals.
- Patient satisfaction remains stable but is impacted by longer wait times during high-demand periods.

---

## Tools & Technologies
- **Power BI**
- DAX (for KPI calculations)
- Data Modeling & Relationships
- Interactive Filters & Slicers
- Custom Visualizations

---

## How to Use
1. Download the Power BI (.pbix) file
2. Open it in **Power BI Desktop**
3. Use **Year and Month slicers** to filter data
4. Navigate between **Monthly**, **Consolidated**, and **Patient Details** views
5. Interact with charts for deeper insights

---

## Conclusion
The ER Performance Tracker provides a comprehensive and interactive way to evaluate emergency room efficiency, patient experience, and operational performance. The dashboard helps healthcare administrators identify trends, optimize resources, and enhance overall service quality.

---



