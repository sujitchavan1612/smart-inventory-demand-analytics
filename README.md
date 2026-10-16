# Smart Inventory & Demand Analytics

## Project Overview
A Python-based data analytics project that explores sales performance, inventory levels, revenue, and estimated profit to support data-driven inventory decisions.

## Objectives
- Analyze sales and inventory data.
- Identify best-selling products and high-revenue categories.
- Compare revenue across regions.
- Calculate revenue, estimated profit, and profit margin.
- Identify records that may require inventory replenishment.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- GitHub

## Dataset
- **Records:** 10,000
- **Original columns:** 17
- **Derived columns:** Revenue, Profit, and Stock_Status, plus any other derived columns in the notebook.

## Key Findings
| Metric | Result |
|---|---:|
| Total quantity sold | 79,973 |
| Total revenue | 1,000,725,318.76 |
| Estimated profit | 314,466,391.30 |
| Estimated profit margin | 31.42% |
| Best-selling product | USB-C Cable |
| Top revenue category | Computers |
| Top revenue region | West |
| Low-stock records | 1,982 |

## Analysis Performed
1. Data inspection and date conversion.
2. Data-quality checks and descriptive statistics.
3. Product-level sales analysis.
4. Category and regional revenue analysis.
5. Revenue and estimated profit calculations.
6. Inventory stock-level analysis.
7. Data visualization using Matplotlib.
8. Export of analyzed data and business summary to CSV files.

## Business Logic
- **Revenue** = Quantity Sold × Unit Price
- **Estimated Profit** = Quantity Sold × (Unit Price − Cost Per Unit)
- **Profit Margin** = Estimated Profit ÷ Revenue × 100
- **Low-stock record** = Current Stock ≤ Reorder Level

## Repository Files
- `inventory_data_cleaning.ipynb` — analysis notebook.
- `inventory_analysis_results.csv` — analyzed dataset.
- `business_summary.csv` — summary metrics.
- `README.md` — project documentation.

## Important Notes
The profit figures are estimates based on the available unit price and unit cost fields. The 1,982 low-stock figure represents records, not necessarily distinct products requiring replenishment. Stock levels should be validated at the appropriate product and date level before operational decisions are made.

## Future Improvements
- Add monthly sales trend analysis.
- Validate reorder requirements using the latest stock level per product.
- Add demand forecasting.
- Develop an interactive inventory dashboard.

## Author
Sujit Chavan

GitHub: [sujitchavan1612](https://github.com/sujitchavan1612)
