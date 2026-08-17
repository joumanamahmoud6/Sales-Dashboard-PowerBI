# Sales Performance Dashboard — Power BI

A sales analytics dashboard built with Power BI Desktop using a star schema data model.

## Dashboard Overview
- **Total Sales**, **Total Orders**, **Avg Order Value**, **Total Tax** KPI cards
- Sales by Territory (column chart)
- Sales Trend Over Time (line chart)
- Orders by Status (chart)
- Top 10 Customers by Sales (bar chart)

## Data Model — Star Schema
![Star Schema](schema/star_schema_diagram.png)

### Tables
| Table | Type | Description |
|---|---|---|
| Fact | Fact | Central sales transactions table |
| Dim_Date | Dimension | Order date hierarchy |
| Dim_Product | Dimension | Product details |
| Dim_territory | Dimension | Sales territory info |
| Dim_Status | Dimension | Order status |
| Dim_ShipMethod | Dimension | Shipping method |

## Tools Used
- Power BI Desktop
- DAX (measures: Total Sales, Total Orders, Avg Order Value, Total Tax)
