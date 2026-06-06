<<<<<<< HEAD
# power-bi-sales-data-analysis
=======
# Power BI Sales Data Analysis

Portfolio project focused on sales performance analysis in Power BI. The report uses a small star-schema dataset with sales facts and customer, product, employee, and geography dimensions.

## Report Preview

### Executive Dashboard

![Executive dashboard](screenshots/exec_dashboard.png)

### Customer Details

![Customer details](screenshots/customer_details.png)

### Sales by Country

![Sales by country map](screenshots/map.png)

## Project Goals

- Analyze total sales, quantity, average sales per order, profit, and customer value.
- Compare sales performance across product categories, countries, and time periods.
- Explore customer loyalty tiers and identify whether loyalty level is connected to customer profitability.
- Build an interactive Power BI report with slicers for category, country, and year.

## Dataset

The dataset contains:

- `FactSales.csv` - transaction-level sales data
- `DimCustomer.csv` - customer attributes and loyalty tiers
- `DimProduct.csv` - product categories
- `DimEmployee.csv` - employee dimension
- `DimGeography.csv` - country and geography data

## Tools Used

- Power BI
- Power Query
- DAX
- CSV data modeling

## Files

- `report/sales_data_analysis_dashboard.pbix` - Power BI report file
- `data/` - source CSV files
- `screenshots/` - report page previews

## Key Findings

- Clothing generated the highest category sales in the report view.
- Monthly sales stayed relatively stable, with a visible peak in December.
- Loyalty tiers showed only a small difference in average customer value, suggesting the tier structure may not strongly separate high-value customers.
>>>>>>> 1e4a4cc (Add Power BI sales analysis project)
