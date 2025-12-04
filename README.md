# dataengineering_nyc_payroll_project
**Project Introduction**
The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:

Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.
You have been hired as a Data Engineer to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.
<img width="496" height="563" alt="image" src="https://github.com/user-attachments/assets/df110817-daf9-4995-bca7-23f5d5c17c38" />

NYC Payroll DB Schema

In the following pages, we will go through the project instructions and by the end you will have built a Data Integration Pipelines on the NYC Payroll Data. We will be using Azure Data Factory to create Data views in Azure SQL DB from the source data files in DataLake Gen2. Then we built our dataflows and pipelines to create payroll aggregated data that will be exported to a target directory in DataLake Gen2 storage over which Synapse Analytics external table is built. At a high level your pipeline will look like below

<img width="574" height="191" alt="image" src="https://github.com/user-attachments/assets/06c6392f-a65e-4b8a-a1c2-d749efbaf488" />

High level Pipeline Overview
