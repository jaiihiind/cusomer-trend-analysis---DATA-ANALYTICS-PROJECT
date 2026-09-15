# Analyst Notes

## Purpose
This file records the additional analysis decisions made while customizing the base project.

## Dataset snapshot
- Rows: 3,900
- Columns: 18
- Total purchase revenue: $233,081
- Average purchase amount: $59.76

## Additional analytical checks
1. Built a category performance summary using transaction count, average purchase, and revenue.
2. Added customer value bands based on purchase amount.
3. Compared discounted vs. non-discounted transactions.
4. Reviewed purchase-frequency behavior.
5. Added SQL questions for high-value repeat customers, payment-method performance, and frequency-level revenue.

## Interpretation
The dataset suggests that Clothing is the largest revenue-generating category, while subscription status does not create a large difference in average purchase value. Discounted transactions also have a slightly lower average purchase amount in this sample, which is worth investigating before assuming discounts automatically increase basket value.

## Reproducibility
All figures in this note are calculated from `customer_shopping_behavior.csv` included in this repository.
