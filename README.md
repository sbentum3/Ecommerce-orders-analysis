# E-Commerce Sales & Customer Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-0078D4)
![Data Analysis](https://img.shields.io/badge/Focus-Business%20Intelligence-6f42c1)

## Project Overview

This project analyzes **30,000 e-commerce orders** to understand the key drivers of revenue, profitability, customer retention, product performance, marketing acquisition, and delivery performance.

The analysis was developed in **Power BI**, using a structured data model, calculated measures, time-intelligence calculations, customer segmentation, and interactive dashboards.

The objective was not only to report sales performance, but to identify **where revenue is being generated, where profitability is being lost, and which customer and operational segments require management attention.**

---

## Business Questions

The dashboard was designed to answer questions such as:

- How are revenue, orders, units and profit performing over time?
- Which categories, brands and products drive revenue and profit?
- Are high-revenue categories also the most profitable?
- How does discounting affect order value and profitability?
- How important are returning customers?
- Which countries and cities contribute the most revenue?
- Which acquisition channels generate the most value?
- How does device usage differ across customers?
- Are delivery speed and shipping methods affecting commercial performance?

---

## Dataset

The dataset contains **30,000 order-level transactions** with information covering:

- Order and customer identifiers
- Order dates
- Product and category information
- Brand
- Quantity
- Unit price
- Discount
- Revenue
- Profit
- Customer segment
- Membership status
- Country and city
- Device type
- Traffic source
- Shipping method
- Delivery time
- Product ratings

### Portfolio scale

| Metric | Value |
|---|---:|
| Orders | **30,000** |
| Customers | **8,683** |
| Products | **2,500** |
| Units sold | **92,420** |
| Revenue | **$11.37M** |
| Profit | **$2.22M** |
| Overall profit margin | **19.5%** |
| Average order value | **$379** |

---

## Data Model & Power BI Development

The Power BI report uses a structured analytical model built around order-level facts and supporting dimensions.

Key modelling components include:

- `Facts_Orders`
- `Dim_Customer`
- `Dim_Date`
- Product/category attributes
- Dedicated DAX calculation layer

### Key Power BI techniques

- Data modelling and relationships
- DAX measures
- Time intelligence
- Year-over-year analysis
- Dynamic KPI calculations
- Customer segmentation
- Conditional formatting
- Interactive slicers and drill-downs
- Category, geography and channel analysis

---

# Key Business Insights

## 1. Electronics drives revenue but underperforms on margin

Electronics generated approximately **$6.32M**, representing **55.6% of total revenue**.

However, its profit margin was only **16.2%**.

This compares with:

| Category | Profit Margin |
|---|---:|
| Beauty | **28.9%** |
| Fashion | **25.8%** |
| Home & Kitchen | **21.2%** |
| Electronics | **16.2%** |

### Business implication

Electronics is the company's primary revenue engine, but its contribution to profit is disproportionately weaker.

Management should therefore evaluate electronics performance using **profit and margin**, rather than revenue alone.

Potential areas for investigation include:

- Supplier/product costs
- Discounting
- Shipping costs
- Product mix
- Pricing strategy

---

## 2. Higher discounts are associated with weaker profitability

The analysis shows a consistent deterioration in profitability as discounts increase.

| Discount Band | Avg. Order | Profit Margin |
|---|---:|---:|
| 0% | $427.84 | **25.0%** |
| 1–5% | $407.38 | 23.9% |
| 6–10% | $381.75 | 22.5% |
| 11–15% | $371.13 | 21.4% |
| 16–20% | $355.52 | 19.9% |
| 21–30% | $320.17 | 18.7% |
| 31%+ | $299.68 | **16.2%** |

The correlation between discount percentage and profit margin is approximately **-0.29**.

### Business implication

Aggressive discounting appears to increase the risk of sacrificing profitability.

A more targeted discount strategy could focus discounts on:

- Customer acquisition
- Slow-moving products
- Strategic product bundles
- High-margin products

rather than applying large discounts broadly.

---

## 3. Returning customers are a major revenue contributor

Returning customers generated approximately:

- **$4.58M revenue**
- **$888K profit**
- **11,987 orders**

This represents approximately **40% of total revenue**.

Approximately **87.7% of customers have placed multiple orders**, indicating a strong repeat-purchase component within the customer base.

### Business implication

Customer retention is an important commercial asset.

The business could increase customer lifetime value through:

- Personalized recommendations
- Loyalty incentives
- Cross-selling
- Repeat-purchase campaigns
- Targeted email marketing

---

## 4. High-value orders generate most revenue but have lower margins

High-value orders represented approximately **25% of orders**, but generated about **71.5% of total revenue**.

However:

- High-value order margin: **19.1%**
- Other-order margin: **22.9%**

### Business implication

Large orders are essential for revenue generation, but they are not necessarily the most profitable.

Management should investigate whether high-value orders receive:

- Larger discounts
- Lower-margin product combinations
- Higher fulfilment costs
- More expensive shipping arrangements

This is an important example of why **revenue growth should be evaluated alongside profitability**.

---

## 5. Mobile is the dominant customer channel

Mobile transactions generated approximately **$7.10M**, or **62.4% of total revenue**.

Desktop generated approximately $3.40M, while tablets generated approximately $0.87M.

### Business implication

The mobile customer journey should be treated as a strategic priority.

Potential opportunities include:

- Mobile checkout optimization
- Faster page performance
- Mobile-exclusive promotions
- Personalized recommendations
- Simplified payment flows

---

## 6. Social Media is the leading traffic source by revenue

| Traffic Source | Revenue | Profit |
|---|---:|---:|
| Social Media | **$1.98M** | **$386K** |
| Direct | $1.95M | $385K |
| Email | $1.90M | $376K |
| Organic Search | $1.88M | $355K |
| Paid Ads | $1.83M | $350K |
| Referral | $1.83M | $363K |

Social Media generated the highest revenue, but Direct and Email showed slightly stronger profitability.

### Business implication

Marketing channels should be evaluated using **profitability and customer value**, not acquisition revenue alone.

---

## 7. Saudi Arabia presents a potential delivery-performance opportunity

Saudi Arabia generated approximately **$1.20M in revenue**, making it the highest-revenue country in the dataset.

However, its average delivery time was approximately **5.19 days**.

This compares with approximately:

- Australia: 4.08 days
- France: 4.05 days
- US: 4.17 days
- UK: 4.20 days

### Business implication

A high-revenue market with relatively slower delivery warrants further operational investigation.

Potential areas include:

- Fulfilment capacity
- Last-mile delivery
- Inventory positioning
- Courier performance
- Regional warehouse strategy

---

## 8. Faster shipping is associated with larger baskets

Average order values by shipping method were approximately:

| Shipping Method | Avg. Order | Delivery |
|---|---:|---:|
| Same Day | **$396.72** | 1.67 days |
| Express | $383.95 | 3.31 days |
| Standard | $376.31 | 5.28 days |

The margin across shipping methods was relatively similar at approximately **22%**.

### Business implication

Premium delivery customers appear to place somewhat larger orders.

This creates an opportunity to test whether faster delivery can be used as a value-added service without materially damaging margins.

---

# Recommendations

Based on the analysis, five priorities emerge:

### 1. Protect electronics profitability

Monitor electronics at product and brand level to identify products generating high revenue but weak margins.

### 2. Introduce discount guardrails

Review discounts above 20%, particularly where they do not generate meaningful incremental volume or customer retention.

### 3. Strengthen customer retention

Use customer purchase history to develop personalized cross-selling, loyalty and repeat-purchase campaigns.

### 4. Optimize high-value orders

Investigate why high-value orders have lower margins and identify opportunities to improve pricing, product mix and fulfilment economics.

### 5. Improve high-revenue delivery markets

Prioritize logistics analysis in markets such as Saudi Arabia where revenue is high but delivery performance is comparatively slower.

---

# Dashboard Structure

The Power BI report is organized into three main analytical areas:

### Overview

Provides an executive view of:

- Revenue
- Profit
- Orders
- Units
- YoY performance
- Brand/category performance
- Geography
- Membership
- City performance

### Customer Analysis

Explores:

- Customer count
- Customer lifetime value
- Orders per customer
- Customer segments
- Membership
- Gender
- Age
- Country
- Repeat purchasing

### Product & Operations Analysis

Examines:

- Product performance
- Categories
- Brands
- Ratings
- Discounts
- Shipping costs
- Delivery time
- Traffic sources
- Shipping methods
- Day-of-week trends

---

# Skills Demonstrated

**Business Intelligence**

- Power BI
- Dashboard design
- KPI development
- Business storytelling

**Data Analysis**

- Exploratory data analysis
- Customer segmentation
- Profitability analysis
- Trend analysis
- Cohort/customer behaviour analysis
- Geographic analysis

**Data Modelling**

- Fact/dimension modelling
- Relationships
- Date dimension
- Analytical measures

**DAX**

- Measures
- Time intelligence
- YoY calculations
- Dynamic KPIs
- Conditional formatting

**Business Analysis**

- Revenue and margin analysis
- Pricing and discount analysis
- Customer retention
- Marketing channel analysis
- Operational performance
- Data-driven recommendations

---

# Project Outcome

This project demonstrates how Power BI can be used to move from **raw transactional data to actionable business decisions**.

The analysis identifies a number of important commercial themes:

> **Revenue concentration is high, profitability varies materially by category, discounting is associated with margin erosion, returning customers represent a significant share of revenue, and operational performance varies across markets.**

Rather than treating dashboard metrics as isolated KPIs, the project connects **sales, customers, products, marketing and operations** to identify the factors most relevant to business performance.

---

## Repository Structure

```text
Ecommerce-PowerBI-Analytics/
│
├── Ecommerce_orders.pbix
├── ecommerce_orders_dataset.csv
├── README.md
│
└── screenshots/
    ├── overview.png
    ├── customer_analysis.png
    └── product_analysis.png
```

---

## Author

**Samuel Bentum**

Data Analyst | Credit & Portfolio Analytics | Business Intelligence

Skills: **Power BI • DAX • SQL • Python • Excel • Data Analytics**

