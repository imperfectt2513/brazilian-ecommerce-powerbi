\# Brazilian eCommerce — Power BI Dashboard



Interactive Power BI dashboard analyzing 99,441 orders from the Brazilian eCommerce dataset (2016–2018).



\## Dashboard Preview



\### Revenue Analysis

!\[Revenue Analysis](revenue\_analysis.png)



\### Trend Analysis

!\[Trend Analysis](trend\_analysis.png)



\### City \& Category Analysis

!\[City \& Category Analysis](city\_category.png)



\### City Detail (Drill-through)

!\[City Detail](city\_detail.png)



\### Geographic Analysis

!\[Geographic Analysis](geographic\_analysis.png)



\## Dashboard Pages



\- \*\*Revenue Analysis\*\* — 7 KPI cards, revenue by category, dynamic titles, category slicer

\- \*\*Trend Analysis\*\* — YTD revenue, MoM growth %, last year comparison, year slicer

\- \*\*City \& Category Analysis\*\* — Top 5 cities (RANKX + conditional formatting), top 10 categories, drill-through

\- \*\*City Detail\*\* — Drill-through page with revenue, orders and category breakdown per city

\- \*\*Geographic Analysis\*\* — Map visual, revenue by state



\## DAX Measures Built



`Total Revenue` · `Total Orders` · `Avg Order Value` · `YTD Revenue` · `Last Year Revenue` · `MoM Growth %` · `City Revenue Rank` · `Category Revenue Rank` · `Running Total Revenue` · `Dynamic Title` · `Total Customers` · `Revenue Per Customer`



\## Key Business Insights



\- São Paulo generates \~40% of total revenue

\- Coastal Brazil dominates — inland regions are untapped market opportunity

\- Rio de Janeiro = premium city (high AOV, low order volume)

\- 99,441 customers = 99,441 orders → zero repeat customers across 2 years

\- Divinópolis — 1 order worth 36K BRL (likely B2B outlier)

\- April peak revenue across all categories



\## Tools Used



\- Power BI Desktop

\- DAX (CALCULATE, RANKX, TOTALYTD, SAMEPERIODLASTYEAR)

\- Data source: Brazilian eCommerce dataset (Kaggle)



\## Related Projects



\- \[Brazilian eCommerce SQL + Excel Analysis](https://github.com/imperfectt2513/brazilian-ecommerce-analysis)

