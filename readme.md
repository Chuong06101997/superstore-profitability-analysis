# Profitability Improvement Analysis

## Business Context

Superstore generated $2.3M in sales from over 5,000 orders.

Although revenue continued to grow, profit margin declined to 12.47% and 20.40% of orders generated negative profit.

The objective of this project was to identify the drivers of margin deterioration and evaluate potential actions to improve profitability.

---

## Investigation Approach

Rather than analyzing metrics independently, the investigation followed a root-cause framework:

1. Which products contribute most to losses?
2. Are losses concentrated in specific regions?
3. Is discounting associated with declining profitability?
4. Could operational factors explain the margin decline?
5. What business actions could improve profitability?

---

## Key Findings

### Product Analysis

Furniture was the least profitable category.

Further analysis showed that losses were primarily driven by Tables and Bookcases.

Interestingly, Tables generated losses through many moderately unprofitable products, while Machines generated losses through a smaller number of severely unprofitable products.

### Regional Analysis

Losses from Tables and Bookcases were concentrated in the Central region.

Central recorded the lowest margin among all regions (7.92%), suggesting that profitability issues were not evenly distributed across the business.

### Supply Chain Validation

Delivery time, shipping mode, and shipping cost showed limited association with profitability.

This helped eliminate logistics as a primary explanation for declining margins.

### Discount Analysis

Higher discount levels were consistently associated with lower profitability across products and regions.

The relationship remained visible after drilling into category and regional dimensions.

---

## Business Simulation

A What-If parameter was implemented in Power BI to simulate discount-cap scenarios.

At a 30% discount cap:

* Margin increased from 12.47% to 20.19%
* Loss orders decreased from 20.40% to 14.63%
* Profit increased from $286K to $411K

Furniture accounted for 58% of affected orders, indicating that discount governance could significantly improve profitability.

---

## Technical Implementation

Tools:

* Power BI
* Power Query
* DAX

Key Techniques:

* Star Schema Data Model
* DAX Measures
* What-If Parameters
* Dynamic KPI Cards
* Drill-down Analysis
* Cross-dimensional Investigation

