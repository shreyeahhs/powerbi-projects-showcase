# Sales Performance & Profitability Dashboard (Power BI)

## Project Description

This project presents a comprehensive analytical study of sales performance and profitability using an interactive Power BI dashboard.

The dashboard is designed to move beyond surface-level revenue reporting and instead examine how profit is generated, distributed, and sustained across different markets, regions, countries, product categories, and time periods. It supports both high-level executive overview and detailed analytical exploration.

The analysis focuses on understanding not only how much is sold, but where value is created, which segments drive profitability, and how performance evolves over time.

---

## Objectives

The objectives of this project are to:

1. Analyse overall business performance using key commercial indicators
2. Compare customers, orders, sales, and profit at a summary level
3. Identify the most profitable markets, regions, and countries
4. Examine profit contribution by product category
5. Track monthly profit trends and seasonal patterns
6. Analyse profit as a percentage of sales to assess margin efficiency
7. Provide an interactive decision-support tool for business stakeholders

---

## Scope of Analysis

- Geographic scope: Global, with drill-down to market, region, and country level
- Time span: Multiple calendar years (2019–2022)
- Business domains:
  - Sales
  - Orders
  - Customers
  - Profitability
- Level of data: Transaction-level data aggregated for analysis

---

## Data Sources

The dashboard is built using structured retail and sales transaction data commonly used in business intelligence and analytics use cases.

### Dataset Characteristics

- Transaction-level sales records
- Multiple years of historical data
- Standardised product categories
- Consistent geographic hierarchies

### Key Variables

| Category | Description |
|--------|-------------|
| Order Date | Transaction date |
| Customer ID | Unique customer identifier |
| Order ID | Unique order identifier |
| Market | Global market grouping |
| Region | Sub-regional classification |
| Country | Country of sale |
| Product Category | Furniture, Office Supplies, Technology |
| Sales | Revenue value |
| Profit | Net profit value |

---

## Data Preparation & Modelling

### Cleaning and Transformation

- Standardised geographic naming conventions
- Created calendar and time intelligence fields
- Validated sales and profit calculations
- Ensured consistency across product categories
- Removed duplicate and incomplete records

### Data Model

A star-schema style data model was implemented:

- Fact table:
  - Sales and profit transactions
- Dimension tables:
  - Date
  - Geography (Market, Region, Country)
  - Product Category
  - Customer

This structure enables efficient filtering, drill-down, and cross-visual interaction.

---

## Dashboard Structure & Visuals

### 1. Executive KPI Overview

Top-level KPI cards provide a snapshot of business performance:
- Total Customers
- Total Orders
- Total Profit
- Total Sales

These indicators support quick, high-level assessment.

---

### 2. Profit Trend Analysis (Monthly)

A time-series line chart tracks profit by month, allowing identification of:
- Seasonal patterns
- Periods of growth and decline
- Volatility in profitability

---

### 3. Profit by Market

A donut chart visualises the share of total profit contributed by:
- Europe
- Asia Pacific
- US & Canada
- Latin America
- Africa

This highlights geographic concentration of value generation.

---

### 4. Profit by Country

A ranked bar chart compares profit across countries, enabling:
- Identification of top-performing countries
- Detection of underperforming markets
- Geographic benchmarking

---

### 5. Profit by Product Category Over Time

A stacked area visual shows how profit evolves across:
- Furniture
- Office Supplies
- Technology

This reveals category dominance, diversification, and shifts over time.

---

### 6. Profit Percentage of Sales

A combined bar and line visual compares:
- Total Sales
- Total Profit
- Profit as a percentage of sales

This provides insight into margin efficiency rather than absolute value alone.

---

### 7. Profit by Region

A regional comparison highlights how profitability differs across:
- Western Europe
- Eastern Asia
- Southern Asia
- Central America
- Oceania

---

## Key Findings

### 1. Profit Concentration Is Uneven

A small number of markets and countries contribute a disproportionate share of total profit, indicating reliance on specific regions.

---

### 2. Technology Drives the Highest Profit

The Technology category consistently generates the highest profit compared to Furniture and Office Supplies.

---

### 3. Seasonal Profit Patterns Exist

Monthly analysis shows clear seasonality, with profit peaks occurring in specific quarters, suggesting demand-driven cycles.

---

### 4. High Sales Do Not Always Mean High Margins

Some periods and regions show strong sales volumes but lower profit percentages, highlighting margin pressure.

---

### 5. Regional Performance Varies Significantly

Western Europe and select Asian regions outperform others in terms of both absolute profit and margin efficiency.

---

## Interpretation & Implications

### Business Strategy
- Focus investment on high-margin categories and regions
- Re-evaluate pricing or cost structures in low-margin markets

### Operations
- Plan inventory and staffing around seasonal profit peaks
- Optimise supply chains in underperforming regions

### Analytics
- Demonstrates the importance of analysing profit alongside sales
- Highlights the value of multi-dimensional interactive dashboards

---

## Limitations

- Analysis is based on historical data only
- External factors such as inflation and exchange rates are not modelled
- Profit calculations assume consistent cost structures
- Customer-level behavioural analysis is limited

---

## Future Enhancements

- Customer segmentation and lifetime value analysis
- Discount and promotion impact analysis
- Forecasting and predictive modelling
- Drill-through to order-level profitability
- Integration of operational cost data

---

## How to Use the Dashboard

1. Select the desired year using the year filter
2. Switch between Customers, Orders, Sales, and Profit views
3. Use slicers to explore markets, regions, and countries
4. Hover over visuals for detailed tooltips
5. Compare trends across time and product categories

---

## Tools & Technologies

- Power BI
- DAX
- Data modelling best practices
- Interactive visual analytics

---

## Intended Audience

- Business analysts
- Data analysts
- Commercial and sales managers
- Strategy and operations teams
- Students and portfolio reviewers

---

## License & Usage

This project is shared for educational, learning, and portfolio purposes.
You are free to reuse and adapt the work with attribution.

---

Built with ❤️ by 
**Shreyas Gowda**  
*MSc Data Science*  
*University of Glasgow*

Note: OpenAI GPT-5.2 was used as a support tool to improve clarity, structure, and analytical articulation.
