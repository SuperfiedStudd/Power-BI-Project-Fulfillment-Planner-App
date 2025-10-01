# Power-BI-Project-Fulfillment-Planner-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.project-fulfillment-planner?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/DI4Zz4ET3DQ/0.jpg)](https://youtu.be/DI4Zz4ET3DQ?si=2oLnIy8KqKUeF10t)  

---

## Overview  

Delivering large-scale projects efficiently demands sharp oversight of timelines and vendor capabilities. The **Project Fulfillment Planner Dashboard** equips project managers with tools to compare subcontractor performance, evaluate project durations, and build efficient vendor-job matches.  

With job-, project-, and vendor-level insights, this Power BI app empowers businesses to reduce delays, assign work strategically, and complete projects with greater reliability.  

---

## Technical Framework  

The dashboard is built on a multi-table model combining job records, project data, and subcontractor performance metrics.  

**Key components:**  
- **Data Source:** Excel or system exports containing job IDs, project plans, and subcontractor job records  
- **Data Preparation (Power Query):**  
  - Merged tables on Job ID  
  - Cleaned and standardized project/job/subcontractor fields  
  - Calculated average completion time and job count per contractor  
  - Created matrix for performance comparisons  
- **Data Model Tables:**  
  - **Projects Table:** Job ID, Project ID, Target Days  
  - **Jobs List Table:** Job ID  
  - **Subcontractor Performance Table:** Job ID, Subcontractor, Completion Time (Days)  

This model supports deep analysis of how different vendors perform across job types and projects.  

---

## Interactive Filters  

The dashboard offers the following slicers for customizable analysis:  
- **Subcontractor Filter:** See job history and performance for any vendor  
- **Project Filter:** Analyze target vs. actual timelines by project  
- **Job Filter:** Drill down to specific job types for vendor comparison  

All visuals update dynamically to support real-time planning and vendor evaluation.  

---

## Dashboard Highlights  

**KPI Tiles – Project Execution Overview**  
- Avg. Target Days – Mean expected duration for projects  
- Avg. Completion Time (Days) – Actual average completion across jobs  
- No. of Jobs / Projects – Scope of analysis  
- Subcontractor Count – Vendor base involved in fulfillment  

**Matrix – Job Completion Time by Subcontractor**  
- Visual heatmap of completion times by job and subcontractor  
- Helps choose the fastest and most reliable vendors for each task  

**Project Table – Target Days by Project**  
- Lookup table to reference project IDs and their target durations  
- Enables side-by-side comparison with actual performance  

This dashboard transforms subcontractor selection into a data-driven process—improving project planning accuracy, vendor accountability, and overall execution speed. Perfect for organizations managing multiple workflows and external partnerships.  

---

## Screenshot  

### Dashboard Overview  
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Project-Fulfillment-Planner-App/blob/main/docs/dashboard_overview.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshot for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.project-fulfillment-planner?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

For organizations balancing multiple subcontractors and projects, visibility is key. This dashboard ensures better planning, stronger vendor accountability, and reduced delays—driving efficiency and reliability in project execution.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
