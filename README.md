# E-Commerce Sales & Profit Dashboard

An Excel dashboard that shows which products and payment methods drive sales and profit, and where the business loses money. Built for Data Forge Challenge #002.

## Dashboard preview

![Dashboard](images/dashboard.png)

## Business question

Which products and payment modes drive revenue and profit, and how can losses be reduced and margins improved?

## Dataset

1,500 order line items across 500 unique orders, with amount, profit, quantity, category, sub-category and payment mode (COD, Credit Card, Debit Card, UPI, EMI). Amounts are in Indian rupees (₹).
Source: Data Forge Challenge #002 (add the link to the original dataset repository here).

## Tools

- Microsoft Excel 2024
- Excel Tables, PivotTables, PivotCharts, Slicers

## Method

- Kept the original data untouched and cleaned a copy
- Checked for missing values, duplicate line items and impossible values
- Treated repeated order IDs as normal, because one order can have several items
- Added helper columns: loss flag, quantity band, first-line-of-order flag and a clean-row flag
- Built every KPI and chart from PivotTables, with slicers for payment mode and category

## Key metrics

| Metric | Value |
|---|---|
| Total sales | ₹437,771 |
| Total profit | ₹36,963 |
| Profit margin | 8.4% |
| Loss-making order lines | 35.3% |
| Units sold | 5,615 |
| Average sale per line | ₹292 |

## Key insights

1. **Profit is positive but thin.** Sales of ₹437,771 give a margin of only 8.4%. Clothing earns the best margin, while Electronics has the highest sales but a lower margin.
2. **Profit depends on two products.** Printers (₹8,606) and Bookcases (₹6,516) earn about 41% of all profit.
3. **Five sub-categories lose money.** Furnishings, Electronic Games, Kurti, Skirt and Leggings lose ₹2,296 in total. Across the data, 35.3% of order lines make a loss.
4. **Credit Card is the most profitable way to pay.** Its margin is 15%, against 8% for COD and Debit Card, 6% for EMI and 5% for UPI.
5. **Very large orders earn the thinnest margins.** Lines of 11 or more units earn about 5%, against about 10% for smaller lines.

## Recommendations

- Review prices and discounts on the five loss-making sub-categories, and set a minimum margin per product.
- Protect stock and pricing on Printers and Bookcases, and promote similar high-margin items.
- Encourage card payments, and check the discounts and fees attached to UPI, EMI and COD.
- Cap bulk discounts and set a minimum margin for large orders.
- Review pricing on Electronics, which has high sales but only a modest margin.

## How to use the workbook

1. Download `Sales_Profit_Dashboard.xlsx`.
2. Open it in Excel and click **Data > Refresh All** if prompted.
3. Use the slicers at the top to filter the charts.

## Limitations

- The data has no dates, so trends over time cannot be analysed.
- Profit and margin are measured per order line, not per order.
- Findings describe this dataset and need more data to confirm.

## Author

Faridah Ayomide Uthman
