# SAKSHI Constructions - Building Construction Business Dashboard | Power BI Project

## Overview
The SAKSHI Constructions Dashboard is a comprehensive Business Intelligence solution developed in Power BI to provide end-to-end visibility into construction projects. The project focuses on solving real-world business problems like budget overruns, material cost tracking, and project delay monitoring.

This dashboard converts raw operational data from 4 different tables into 6 interactive and insightful dashboard pages.

## Business Problems Solved
1.  Lack of centralized view for Project Managers to track multiple projects across different cities.
2.  Difficulty in tracking Budget vs. Actual Cost and identifying profit leakage.
3.  No clear visibility on material-wise cost and supplier performance.
4.  Inability to monitor task completion rate and pending tasks.

## Dashboard Structure and KPIs

The project contains 6 pages:

**1. Project Dashboard (Home Page)**
Central navigation page with high-level KPIs:
- Total Revenue: 4 Bn
- Total Budget: 2 Bn
- Total Workers: 28K
- Total Profit: 2 Bn

**2. Project Overview**
Analyzes projects by City (Houston, New York, Chicago etc.) and Project Manager. Helps identify which city has the maximum number of active projects.

**3. Financial Analysis**
Detailed financial health check. Visuals include:
- Budget vs Cost by Project
- Revenue vs Labor Cost vs Material Cost
- Month-wise trend analysis

**4. Material Management**
Focuses on material consumption:
- Profit Contribution by Material Name (Blocks, Bricks, Cement, Concrete, Electrical, Glass, Plumbing, Steel, Wood)
- Material Cost by Project Name
- Supplier-wise analysis

**5. Task Monitoring**
Tracks operational efficiency:
- Average Task Completion: 78.08%
- Total Tasks: 2K
- Task Status: Complete vs In Progress (60.2% In Progress)
- Top tasks by completion %: Site Survey, Excavation, Structural Framing

**6. Performance Summary**
Final summary page consolidating all KPIs - Budget (2Bn), Total Cost (2Bn), Material Cost (185M), Profit (2Bn) and key insights.

## Data Model

**Tables Used (4 Tables):**
- CostTable - Fact table containing financial metrics
- MaterialTable - Dimension table for materials
- ProjectTable - Dimension table for projects
- TaskTable - Dimension table for tasks

**Relationship:** Star Schema was implemented for optimal performance.

**DAX Measures (14+ Measures Created):**
Total Budget, Total Cost, Total Revenue, Total Profit, Total Workers, Total Tasks, Total Material Cost, Total Quantity, Avg Task Completion %, Total Labor Cost and more.

## Key Insights Derived
- The company maintains a healthy profit margin with Total Revenue (4Bn) double the Total Cost (2Bn).
- All 9 materials contribute equally to profit (11.11% each), showing balanced project planning.
- 60.2% of tasks are still in-progress, indicating a need to focus on faster execution.
- Labor Cost and Material Cost trends are stable and well within budget limits.

## Tools and Technologies
- Power BI Desktop
- Power Query for Data Cleaning & Transformation
- DAX (Data Analysis Expressions)
- Data Modeling

## How to Use This Dashboard
1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Refresh data if needed and explore the 6 pages.

## Author
**Sakshi Chitrio**
Aspiring Data Analyst
