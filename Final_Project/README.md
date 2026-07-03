# Sales Uplift Dashboard — Retail Transactions Analysis

This project analyzes retail transaction data to uncover sales trends across regions, categories, sales channels, and time periods, supporting the insights shown in the **Sales Uplift Dashboard**.

## 📊 Dataset Overview

- **Records:** 20,000 transactions
- **Unique Customers:** 3,981
- **Total Sales:** ₹555.60M
- **Time Period:** Full calendar year (January–December)

**Columns:**
- `TransactionID` — Unique identifier for each transaction
- `Date` — Transaction date
- `ProductName` — Name of the product sold
- `Category` — Product category (Electronics, Beauty, Grocery, Sports, Clothing, Furniture)
- `Region` — Sales region (North, South, East, West)
- `SalesChannel` — Offline or Online
- `Quantity` — Units sold
- `UnitPrice` — Price per unit
- `TotalAmount` — Total transaction value
- `PaymentMode` — Cash, UPI, Credit Card, or Net Banking
- `CustomerID` — Unique customer identifier

## 📈 Dashboard Summary

The Sales Uplift Dashboard visualizes this data across several key metrics:
- **Total Sales:** 555.60M
- **Transactions:** 20K
- **Customers:** 4K
- **Average Order Value:** 28K
- Breakdowns by Region, Month, Product, Category, and Sales Channel

## 🔍 Key Insights

See [`Insights.txt`](./Insights.txt) for the full list. Highlights include:
- Sales are nearly evenly distributed across all four regions, with East leading marginally.
- Grocery and Electronics are the top-performing categories.
- Offline (50.6%) and Online (49.4%) channels are almost evenly split.
- October and December see peak sales, likely driven by the festive season, while February is the weakest month.
- UPI is the most-used payment method, closely followed by Cash, Credit Card, and Net Banking.

## 🛠️ How This Was Analyzed

The dataset was processed using **Python (pandas)** to compute aggregate metrics such as total sales by region, category, sales channel, product, month, and payment mode — which were then cross-referenced against the dashboard visuals to validate and expand on the reported figures.

## 📌 Suggested Next Steps

- Investigate the February sales dip and design a targeted promotional campaign.
- Explore online channel growth opportunities to close the gap with offline sales.
- Analyze Furniture category underperformance relative to other categories.
- Segment customers by purchase frequency to identify high-value repeat buyers.
