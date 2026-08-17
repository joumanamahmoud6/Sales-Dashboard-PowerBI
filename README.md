# Sales Performance Dashboard — Power BI

A sales analytics dashboard built with Power BI Desktop using a star schema data model.

## Dashboard Overview
- **Total Sales**, **Total Orders**, **Avg Order Value**, **Total Tax** KPI cards
- Sales by Territory (column chart)
- Sales Trend Over Time (line chart)
- Orders by Status (chart)
- Top 10 Customers by Sales (bar chart)
<img width="1342" height="735" alt="Screenshot 2026-08-17 223717" src="https://github.com/user-attachments/assets/33bb67ab-18e9-4db0-87ff-cc984bfba4ae" />


## Data Model — Star Schema
<img width="1181" height="678" alt="Screenshot 2026-08-17 223735" src="https://github.com/user-attachments/assets/237a448f-30cd-4f8f-b07c-d0bf2659c75e" />

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
