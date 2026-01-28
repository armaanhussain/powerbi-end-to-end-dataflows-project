# End-to-End Power BI Analytics Project (Dataflows-Centric Architecture)

 ## Project Overview
This repository showcases a complete enterprise-level Business Intelligence solution built using Power BI Dataflows, SQL Server, and Power BI Service.
The project demonstrates how to design, develop, validate, and deploy scalable analytics solutions using modern Power BI architecture, focusing on dataflows, advanced DAX, performance optimization, and automated refresh pipelines.

The use case is loan & credit risk analytics, covering loan amounts, default rates, income patterns, credit scores, and demographic analysis.

## Architecture Overview

- Data Source → SQL Server → Power BI Dataflows → Power BI Desktop → Power BI Service

- Microsoft SQL Server as the primary data source

- On-Premises Data Gateway (Standard Mode) for secure data connectivity

- Power BI Dataflows for centralized ETL and reusable datasets

- Power BI Desktop for modeling, DAX, and visualization
- 
- Power BI Service for publishing, scheduling, and incremental refresh

## Tools & Technologies

Data Source: Microsoft SQL Server

ETL & Data Preparation: Power BI Dataflows, Power Query Editor

BI & Visualization: Power BI Desktop, Power BI Service

Gateway: On-Premises Data Gateway (Standard Mode)

Languages & Logic: DAX, SQL

Refresh & Performance: Scheduled Refresh, Incremental Refresh

 ## Key Features & Implementations

🔹 Data Engineering (Dataflows)

- Created Power BI Dataflows for centralized data ingestion and transformation

- Applied data profiling, data type validation, and cleansing in Power Query

- Implemented reusable entities to support multiple reports

- Configured incremental refresh to optimize refresh time and performance

🔹 Data Modeling

- Designed optimized star-schema data models

- Defined proper relationships, cardinality, and filter directions

- Applied best practices for performance and scalability

🔹 Advanced DAX Measures

- Developed complex and optimized DAX calculations including:

- Aggregation & Iteration: SUMX, AVERAGEX, MEDIANX, COUNTROWS

- Context Manipulation: CALCULATE, FILTER, ALL, ALLEXCEPT, VALUES

- Logical & Conditional Logic: SWITCH, NOT, ISBLANK

- Time Intelligence:

  - Year-over-Year (YOY) Loan Amount

  - YOY Default Rate Change

  - Year-to-Date (YTD) Loan Amount

## Analytics & Dashboards

- Built interactive and validated dashboards covering:

  - Loan Amount by Purpose, Age Group, Credit Score & Marital Status

  - Default Rate by Employment Type and Year

  - Income Analysis by Employment Type

  - Credit Risk & Demographic Segmentation

  - Decomposition Tree for root-cause analysis

- Visuals used:

 - Column Charts

 - Line Charts

 - Donut Charts

 - Decomposition Tree

🔹 Data Validation & Quality Checks

- Performed measure-level and visual-level data validation

- Cross-verified DAX results with source data

- Ensured business logic consistency and accuracy

🔹 Deployment & Automation

- Published reports to Power BI Service

- Configured scheduled refresh for datasets and dataflows

- Implemented incremental refresh for scalable production deployment

# 📈 Business Value

- Enables data-driven decision making for loan and credit risk analysis

- Demonstrates enterprise BI best practices using Dataflows architecture

- Optimized refresh and performance for large datasets

- Fully production-ready analytics workflow
