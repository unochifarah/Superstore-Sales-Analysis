# Superstore Sales Analysis
### Excel · Pivot Tables

**By Jasmine Unochi** · [LinkedIn](https://www.linkedin.com/in/jasmine-unochi-4613a3169) · [GitHub](https://github.com/unochifarah)

---

## Overview

The Superstore Sales Dataset is a retail dataset from a global superstore spanning 4 years, consisting of 18 columns and 9,800 rows covering orders, customers, products, and regional sales data.

---

## Questions Explored

1. Which state has the highest sales?
2. Which item has the highest order count?
3. Which item has the highest revenue?
4. Which segment orders the most — and which has the highest revenue?
5. Is there a peak season?
6. Does year-on-year growth exist?
7. Does ship mode actually affect shipping time?
8. Which category sells the most by orders vs revenue?

---

## Process

For each question I identified the relevant columns, built a pivot table, and sorted the results. I also followed up on findings that raised new questions — particularly around the Home Office segment and the recurring gap between order count and revenue.

---

## Findings

- **California dominates** — highest total sales at $446,306, and remains the top state even when filtered to Home Office customers specifically (325 orders)
- **Volume and revenue tell different stories** — the most ordered item is Staple Envelope with 47 orders and $1,675 in total sales, while the highest revenue item is the Canon imageCLASS 2200 Advanced Copier at $61,599 from just 5 orders
- **Home Office punches above its weight** — despite having the fewest orders of the 3 segments, Home Office customers average $243 per order vs Consumer's $225
- **Home Office drill-down** — their preferred ship mode is Standard Class (1,046 orders), top state is California, and most ordered product is Easy-staple Paper
- **Q4 is peak season** — orders spike in September, dip unexpectedly in October, then peak again in November and December. This pattern holds consistently across all 4 years
- **Year-on-year growth is consistent** — order count grew from 1,953 in 2015 to 3,258 in 2018, a 67% increase
- **Ship mode does affect shipping time** — Same Day averages 0 days, First Class 2 days, Second Class 3 days, Standard Class 5 days
- **Technology leads revenue despite low volume** — Office Supplies has the most orders (5,909) but the lowest average order value ($119). Technology has the fewest orders (1,813) but the highest revenue ($827,455) and highest average order value ($456)

---

## Conclusion

A recurring theme across all findings is that order count and revenue consistently tell different stories — the most ordered items, segments, and categories are rarely the most valuable ones.

The company could benefit from paying closer attention to the Home Office segment despite its low order volume, focusing marketing and retention efforts in California, and prioritizing Technology category products where average order value is nearly 4x that of Office Supplies. Bundling strategies targeting Home Office customers in California could be worth exploring to grow both order frequency and order value in the segment that already spends the most per transaction.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Excel | Data exploration, pivot tables, charts |

---

## Dataset

**Source:** [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) via Kaggle
**Records:** 9,800 transactions
**Period:** 2015–2018
**Fields:** Orders, customers, products, sales, shipping, geography
