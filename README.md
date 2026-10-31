# Sales Performance Analysis and Dashboard Using Microsoft Excel

## Project Overview

This project explores historical sales data to understand revenue performance across countries, product lines, deal sizes, and order statuses. Microsoft Excel was used to prepare the dataset, summarize performance with PivotTables, and build a dashboard for communicating key findings.


## Project Objectives

- Analyze overall sales and order volume.
- Compare revenue across countries and product lines.
- Understand the contribution of different deal sizes.
- Review sales by order status.
- Present findings in an interactive, easy-to-read Excel dashboard.

## Dataset Overview

The workbook contains an uncleaned dataset and a cleaned dataset.

- **Records:** 2,823
- **Unique order numbers:** 307
- **Date range:** 6 January 2003 – 31 May 2005
- **Main fields:** order number, quantity ordered, price each, sales, order date, status, product line, customer, city, state, country, territory, and deal size.

## Tools Used

- Microsoft Excel
- Excel formulas
- PivotTables
- Excel charts and dashboard

## Data Preparation

The workbook includes a separate cleaned dataset. The preparation includes date-derived fields for order day, order month, and order year, alongside the removal of some fields from the original dataset.

**Data-quality note:** Missing values in the State field were filled using the most frequent State value across the entire dataset. This is a global mode-imputation approach because the dataset contains multiple countries, this may assign a state to records where that value is not geographically appropriate. The Territory field also contains 1,074 blank values in the cleaned dataset. These limitations should be considered when interpreting geographic results.

The cleaned sheet also contains three empty `Unnamed` columns, which do not contribute to the analysis.

## Key Findings

Based on the cleaned dataset:

- **Total sales:** $10,032,628.85
- **Quantity ordered:** 99,067
- **Unique orders:** 307
- **Highest-revenue country:** USA, with $3,627,982.83
- **Highest-revenue product line:** Classic Cars, with $3,919,615.66
- **Largest sales by deal size:** Medium deals, with $6,087,432.24
- **Most sales revenue by order status:** Shipped, with $9,291,501.08

## Recommendations

1. Continue monitoring country-level sales to understand where revenue is concentrated.
2. Review the performance of the Classic Cars product line and identify factors supporting its contribution.
3. Track order statuses regularly, especially orders that are on hold, disputed, or cancelled.
4. Review deal-size performance to understand how different order values contribute to total revenue.
5. Improve the handling of missing geographic information before using State or Territory fields for detailed location-based decisions.

## Limitations

- The global mode imputation used for missing State values may distort geographic analysis, particularly for records outside the United States.
- The cleaned dataset still contains missing Territory values.
- The workbook does not provide product costs, profit margins, or operating expenses; therefore, this analysis focuses on sales revenue and does not measure profitability.
- The figures describe the period January 2003 to May 2005 and should not be interpreted as current business performance.

## Files

- `SALES DATASET.xlsx` – Excel workbook containing the uncleaned dataset, cleaned dataset, PivotTables, dashboard, and insight/recommendation sheet.
- `README.md` – Project documentation.

---

*This project demonstrates practical data preparation, analysis, and dashboard reporting skills using Microsoft Excel.*
