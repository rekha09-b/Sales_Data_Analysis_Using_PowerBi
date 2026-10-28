# Sales, Profitability & Customer Analysis Dashboard
## Project overview

This report brings key business measures and supporting analysis together in one place. Users can review overall performance, compare results across business dimensions, and filter the report to investigate specific periods, locations, customer segments, or product categories.

The report contains two pages:
### Sales Overview

The Sales Overview page presents the main performance indicators and shows how sales and profit vary across the business. It includes:

- Total Sales, Total Profit, Total Orders, Total Quantity, and Profit Margin KPI cards
- Monthly sales and profit comparison
- Sales and profit by customer segment
- Sales and profit by product category
- Order distribution by shipping mode
- Sales and profit by region

### Profitability and Customer Analysis

The customer analysis page focuses on customer contribution and repeat purchasing. It includes:

- Top 10 customers ranked by sales
- Top 10 customers ranked by profit
- Monthly profit trend
- New versus repeat customer breakdown

## Interactivity

Report slicers allow users to filter by **Year, Region, State, City, Segment,** and **Category**. The visuals update with the selected filters, making it possible to explore performance for a particular part of the business.

## Customer classification

Customers are classified using their distinct order count:

- **New customer:** one distinct order
- **Repeat customer:** more than one distinct order

This logic is implemented with DAX using the customer and order fields in the data model.

## Tools and techniques

- Microsoft Power BI Desktop
- DAX measures and calculated customer classification
- Interactive report pages, KPI cards, charts, and slicers

  ## Repository structure
- Profitability and Customer_Analysis_Dashboard.png
- README.md
- Sales_Overview_Dashboard.png
- sample_data.csv
