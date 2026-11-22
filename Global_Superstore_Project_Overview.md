# Global Superstore Sales Performance Dashboard

An interactive Power BI project built using the Global Superstore dataset. The dashboard helps explore sales, profit, orders, customers, product categories, customer segments, and regional performance.

## Project overview

The report was created in **Microsoft Power BI Desktop**. It includes KPI cards, slicers, and interactive charts to help users analyse sales performance across different years, regions, categories, and customer segments.

## Dashboard features

- **KPI cards:** Total Sales, Total Profit, Total Orders, Average Order Value, Total Customers, Total Quantity Sold, Average Shipping Days, and Profit Margin.
- **Slicers:** Year, Region, Category, and Segment.
- **Customer segment analysis:** Sales by customer segment and category.
- **Regional analysis:** Regional sales and profit summary.
- **Sales trend:** Monthly sales and profit trend.
- **Category analysis:** Sales distribution by product category.
- **Product analysis:** Sales by product name.
- **Geographical view:** Sales and profit by country.

The report is interactive. Selecting a year, region, category, or segment updates the relevant visuals.

## Files in this repository

| File | Description |
|---|---|
| `Dashboard project.pbix` | Power BI Desktop report file. |
| `Global_Superstore_PowerBI_Prepared.xlsx` | Prepared workbook used as the dashboard data source. |
| `Global_Superstore_PowerBI_Project_Pack.zip` | Supporting project pack containing the prepared workbook, Power Query scripts, DAX measures, theme, preview, and report plan. |
| `archive.zip` | Original source dataset archive. |

*File names may differ slightly depending on the names used when uploading them to GitHub.*

## Tools and technologies

- Microsoft Power BI Desktop
- Power Query (data preparation and transformation)
- DAX (measures and calculations)
- Microsoft Excel
- GitHub (project version control and sharing)

## Dataset

The project uses the Global Superstore sample dataset. The prepared workbook contains the `Orders_Prepared`, `Returns`, and `People` tables. The Orders table includes additional analysis fields such as Year, Month, Ship Days, Returned, and Profit Margin.

## How to open the project

1. Download or clone this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. If Power BI asks for the data source, point it to `Global_Superstore_PowerBI_Prepared.xlsx`.
4. Select **Refresh** if required.

## Notes

- The `.pbix` file is the main interactive Power BI report.
- The ZIP file is a supporting resource pack; it is not a replacement for the `.pbix` report.
- Dashboard values change when slicers or filters are selected.

## Author

Created as a practical project for learning data preparation, data modelling, DAX, and interactive dashboard development in Power BI.
