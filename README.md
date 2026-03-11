# 🏍️ Revving Up Revenue: Motorcycle Parts Sales Analysis

[![View the Full Report](https://img.shields.io/badge/View_Final_Report-Blue?style=for-the-badge)](INSERT_YOUR_PUBLISHED_LINK_HERE)

## 1. Project Background and Overview
As a data analyst for a regional motorcycle parts distributor, I was tasked by the Board of Directors to evaluate our summer sales performance (June – August 2021). Our company operates out of three primary distribution centers and serves two distinct markets: B2B Wholesale clients and B2C Retail customers. 

The primary goals of this project were to:
* **Segment Revenue:** Identify the core drivers of revenue by product line and warehouse.
* **Optimize Margins:** Quantify the hidden costs associated with payment methods and processing fees.
* **Evaluate Operational Efficiency:** Analyze physical inventory movement against net revenue generated.

## 2. Data Structure Overview
The analysis was performed on a dataset of 1,000 granular transaction records. The core data structure includes:

| Category | Variables Included |
|----------|-------------------|
| **Logistics** | `order_number`, `date`, `warehouse` (Central, North, West) |
| **Product & Client** | `client_type` (Wholesale/Retail), `product_line`, `quantity` |
| **Financials** | `unit_price`, `total`, `payment` (Cash/Card/Transfer), `payment_fee` |

## 3. Executive Summary

> [!IMPORTANT]
> **Key Findings:**
> * **Wholesale is the Growth Engine:** While Retail revenue declined over the summer, Wholesale revenue grew by 25%, peaking at over $60,000 in August.
> * **High Volume ≠ High Margin:** "Breaking system" parts account for massive physical inventory movement but generate only half the revenue of our "Suspension & traction" parts.
> * **Margin Leakage:** The company lost over $4,800 to payment processing fees in just three months, heavily driven by Retail credit card usage and Wholesale bank transfers.

## 4. Insights Deep Dive
* **The Wholesale Engine vs. Retail Stagnation:** The average Wholesale order is roughly $500 (23 parts), while the average Retail order is only $167 (5 parts). Retail sales dipped to $37,811 in August, making B2B relationships critical for Q4.
* **Product Velocity:** "Suspension & traction" is our most efficient product line, moving 2,145 units to generate $73,539. In contrast, "Breaking systems" required the same physical warehouse labor (2,130 units) but generated only $38,350.
* **The Cost of Convenience:** Retail clients almost exclusively use Credit Cards (costing $3,323 in 3% processing fees). Wholesale clients rely on Bank Transfers, which, despite a lower 1% fee, cost the company $1,582 due to massive purchasing volume.

## 5. Strategic Recommendations

> [!TIP]
> **Action Plan & Next Steps:**
> 1. **Renegotiate B2B Payment Terms:** Finance should leverage our high transaction volume to negotiate a flat monthly rate with our banking partners rather than paying a 1% per-transaction fee on Wholesale transfers.
> 2. **Implement Retail Cash Incentives:** Introduce a "2% Cash Discount" at retail counters to incentivize consumers to skip the credit card, immediately recovering lost margin.
> 3. **Optimize Warehouse Shelving:** Re-evaluate minimum holding inventory for low-margin brake parts to free up warehouse space for our high-revenue "Suspension" and "Frame" components ahead of the Q4 rush.

---
*Created using Python, SQL, DuckDB, Pandas, Seaborn, Matplotlib, Jupyter, HTML/CSS*
