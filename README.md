# Internet-Sales-Analysis

## Introduction
This Power BI project enhances Internet sales reporting through dynamic visual dashboards that analyze and present sales data across products, customers, and sales performance metrics.

## Technologies Used
- **SQL Server**: For database management and data manipulation.
- **Microsoft Power BI**: Used to create dynamic and interactive dashboards.

## Features of the Dashboard
The dashboard is divided into three main sections, each focusing on different aspects of sales data:

1. **Sales Overview Dashboard**: Provides a high-level view of sales performance against the budget and breaks down sales by product categories and customer locations.

2. **Customer Details Dashboard**: Analyzes sales by customer demographics, showcasing sales distribution by city and identifying top customers by sales volume.

3. **Product Details Dashboard**: Details sales data for specific products, including monthly sales trends and geographic distribution of sales.

## Data Sources
Data is sourced from the AdventureWorks sample database, offering a comprehensive set of internet sales and product information.

## Files in the Repository
- **Documents**:
  - `RequirementsMail.docx`: Requirement mail from Steven detailing the project needs.
  - `BusinessDemandOverview.docx`: Document outlining the business demand overview created after analyzing the requirements.
  - `Internet_Sales_Database_Update_Queries.txt`: SQL queries used to update the database before use.
  - `Cleaned_Tables_Queries.txt`: SQL queries used to prepare data tables for dashboard integration.
- **Data Files**:
  - `DimCustomers_Cleaned.csv`
  - `DimDates_Cleaned.csv`
  - `DimProducts_Cleaned.csv`
  - `FactInternetSales_Cleaned.csv`: Cleansed data files used in the dashboard.
- **Additional Files**:
  - `SalesBudget.xlsx`: Sales budget file for comparing actual sales against projections.
  - `Internet_Sales_Dashboard.pbix`: Power BI dashboard file containing three dashboards: Sales Overview, Customer Details, and Product Details.

## Installation and Setup
1. Install SQL Server and SQL Server Management Studio.
2. Restore the AdventureWorks database.
3. Install Microsoft Power BI.
4. Clone this repository and follow the detailed setup instructions provided.

