# Greater-London-property-dashboard
[📂 Download Power BI Dashboard (.pbix)](https://drive.google.com/drive/folders/1_7ChQDp88tq3UBI5IvPJgY_0T7o6C_rD?usp=sharing)

Project Overview

The Greater London Property Price Monitor Dashboard is an analytical visualization project designed to explore property market trends across London, UK from 2020 to 2023.

Using Microsoft SQL Server for data processing and Power BI for visualization, this dashboard transforms raw government property transaction data into interactive, data-driven insights — revealing how property types, duration, and locations influence housing prices in Greater London.

This project was developed for a research organization aiming to create a real-time property monitoring tool to track housing trends and support better investment, policy, and pricing decisions.

 Objectives

To analyze and visualize property transaction trends in London from 2020–2023

To understand how property type, duration (old vs. new), and location impact property prices

To identify monthly and yearly changes in the real estate market

To develop an interactive Power BI dashboard using SQL-based data integration

 Methodology
1. Data Source

Dataset: UK Government Price Paid Data

Files used: pp-2020, pp-2021, pp-2022, pp-2023

Data includes property type, price paid, transaction month, and duration (old/new).

2. Data Preparation
Step 1: Importing Data

Downloaded datasets from official UK data repository

Imported into SQL Server using “Import Flat File” wizard

Step 2: Database Creation

Created a new database named SQLTASK1

Each year’s dataset (pp-2020 to pp-2023) stored in separate tables

Step 3: Data Cleaning

Renamed columns and changed data types for consistency

Added primary keys and handled null values

Unified datasets using SQL UNION function

Step 4: Combining Datasets in Power BI

Imported cleaned data from SQL into Power BI

Created a combined table:

CombinedTable = UNION(PP_2020, PP_2021, PP_2022, PP_2023)

Tools & Technologies Used
Tool	Purpose
Microsoft SQL Server	Data cleaning, structuring, and integration
Power BI	Dashboard creation and visualization
Excel	Preprocessing and initial dataset review
