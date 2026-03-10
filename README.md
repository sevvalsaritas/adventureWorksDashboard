# AdventureWorks Sales Analysis Dashboard

This project presents an interactive **Power BI dashboard** built using the **AdventureWorks sample database** from Microsoft SQL Server. The dashboard analyzes sales performance, product trends, and customer metrics through clear and interactive visualizations.

The purpose of this project is to demonstrate **data visualization, data modeling, and business intelligence skills using Power BI**.

---

## Project Overview

The AdventureWorks dataset simulates the sales operations of a fictional manufacturing company. Using this dataset, an analytical dashboard was created to explore key business metrics and provide insights into sales performance.

The dashboard helps answer questions such as:

- How do sales change over time?
- Which products generate the most revenue?
- Which product categories perform best?
- How many customers and orders contribute to total sales?

---

## Technologies Used

- Microsoft SQL Server  
- AdventureWorks Database  
- Power BI Desktop  
- SQL  
- Data Visualization  

---

## Dataset

This project uses the **AdventureWorks sample database**, which contains realistic sales and operational data for a fictional company.

The main tables used include:

- `Sales.SalesOrderHeader`
- `Sales.SalesOrderDetail`
- `Sales.Customer`
- `Production.Product`
- `Production.ProductSubcategory`
- `Production.ProductCategory`

---

## Dashboard Features

### KPI Metrics
The dashboard provides key performance indicators including:

- **Total Sales**
- **Total Orders**
- **Total Customers**
- **Total Products**

### Sales Trend Over Time
A time-series visualization showing how sales change over time.

### Top 10 Best Selling Products
A bar chart displaying the products that generate the highest revenue.

### Sales by Product Category
A donut chart showing how sales are distributed across product categories.

### Date Range Filter
An interactive slicer allowing users to filter the analysis by date.

---

## Data Model

The dashboard is built using relationships between several tables in the AdventureWorks database:

- `SalesOrderHeader → SalesOrderDetail`
- `Product → ProductSubcategory → ProductCategory`
- `Customer → SalesOrderHeader`

This relational structure enables accurate aggregation and filtering across the dashboard.

---

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. Refresh the data if necessary.
4. Interact with the dashboard using the available filters and visualizations.

---

## Dashboard Preview

<img width="1178" height="1383" alt="image" src="https://github.com/user-attachments/assets/52ce7f8f-3249-4990-8ac6-3a10a506c49f" />

---

## Author

**Şevval Özlem**

Data Engineer interested in **Data Science, Data Analytics, and AI applications**.

