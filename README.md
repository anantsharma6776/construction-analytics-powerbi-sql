# construction-analytics-powerbi-sql
End-to-end Construction Analytics Project using Power BI, SQL, Power Query, and DAX.
Construction Analytics Dashboard using Power BI & SQL
Project Overview

This project focuses on analyzing construction project performance using Power BI and SQL Server. The objective was to transform raw construction project data into interactive dashboards and business insights for executive reporting, risk analysis, and operational monitoring.

The solution was developed using Power BI, Power Query, DAX, and SQL Server (SSMS) following a star schema data modeling approach.

Business Problem

Construction companies often face challenges in:

tracking project costs
identifying high-risk tasks
monitoring labor and equipment utilization
managing task dependencies
analyzing operational constraints

The goal of this project was to build an end-to-end analytics solution to help management monitor project performance and improve decision-making.

Tools & Technologies Used
Power BI
SQL Server (SSMS)
Power Query
DAX
Excel / CSV Dataset
Data Modeling

Implemented a Star Schema Model using:

Fact Table
Dimension Tables
One-to-Many Relationships
Fact Table
Fact_Constructions
Dimension Tables
Dim_Task
Dim_Risk
Dim_Labour
Dim_Equipment
Dim_Dependency
Dashboard Pages
1. Executive Dashboard
Provides a high-level overview of:

Total Material Cost
Average Task Duration
Total Labor Required
High Risk Tasks
Equipment Utilization
Key Features
KPI Cards
Risk Distribution Analysis
Material Cost Analysis
Labor vs Equipment Monitoring
Interactive Slicers
2. Risk Analysis Dashboard
Focused on project risk monitoring and dependency analysis.

Key Features
Risk Distribution
Cost by Risk Level
Dependency Analysis
Task Duration by Risk
High Risk Cost Monitoring
3. Resource & Operations Dashboard
Focused on operational efficiency and resource optimization.

Key Features
Labor Allocation Analysis
Equipment Usage Monitoring
Resource Constraint Analysis
Site Constraint Analysis
Scatter Plot Analysis
KPIs Implemented
Total Material Cost
Average Task Duration
Total Labor Required
High Risk Tasks Count
Total Equipment Units
Average Dependency Count
Average Resource Constraint Score
Average Site Constraint Score

SQL Analysis Performed
Performed SQL-based business analysis using SSMS including:

Risk analysis
Cost analysis
Dependency analysis
Labor allocation analysis
Equipment utilization analysis
Ranking & Window Functions
CTE-based business queries
DAX Features Used
Aggregation Measures
CALCULATE()
COUNTROWS()
AVERAGE()
Dynamic Titles
Interactive KPI Measures
Business Insights Generated
Identified high-risk and high-cost tasks
Analyzed dependency-heavy operations
Monitored labor and equipment utilization
Evaluated operational bottlenecks
Compared project duration across risk categories

Project Outcome
The project successfully transformed raw construction data into an interactive business intelligence solution enabling:

executive-level reporting
operational monitoring
risk analysis
resource optimization
data-driven decision-making
Skills Demonstrated
Power BI Dashboard Development
Data Modeling
DAX Calculations
SQL Analysis
Power Query Transformations
Business Intelligence Reporting
Data Visualization
Analytical Problem Solving
