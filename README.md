# Retail Performance Command Center

> From raw transactions to the five decisions management should make next.

![status](https://img.shields.io/badge/status-design%20stage-lightgrey) ![sprint](https://img.shields.io/badge/sprint-Weeks%201--2-blue) ![project](https://img.shields.io/badge/portfolio-01%2F08-0891b2)

| | |
|---|---|
| **Category** | BI & Analytics |
| **Domain** | Retail |
| **Stack** | SQL · Python · Power BI · Excel |
| **Status** | 🚧 Scoped — implementation not started |

## Overview

An end-to-end analytics project that turns a retail company's raw sales data into one trusted view of performance. It cleans and models the data in SQL, validates it in Python, and delivers a five-page Power BI dashboard (overview, sales, customers, products, regions) plus a short executive memo with quantified recommendations.

## Business problem

A retail company has large volumes of transaction data, but management has no single, trusted view of revenue, profitability, customers, products and regions.

## What this project demonstrates

- Translating a vague business need into the right KPIs
- SQL data modelling and data-quality validation
- Executive dashboard design in Power BI
- Turning analysis into quantified management recommendations

## Key points

- Star-schema data model (orders, items, products, customers, regions, calendar) built in SQL
- Data-quality checks in Python before any KPI is trusted (duplicates, nulls, margin anomalies)
- Core KPIs: revenue, gross profit, margin, AOV, growth, revenue by region and product
- Drill-down answers to: what drives growth, where margins erode, which regions and products underperform
- 1-page executive memo: 3–5 actions, each with an estimated revenue or margin impact
- Data-flow diagram and README written for a non-technical manager

## Planned architecture

```text
Raw transactions
   ↓
SQL data preparation (star schema)
   ↓
Python validation & EDA
   ↓
Business KPIs
   ↓
Power BI dashboard (5 pages)
   ↓
Executive memo & recommendations
```

## Planned deliverables

- [ ] SQL scripts and clean dataset
- [ ] Python validation / EDA notebook
- [ ] Power BI dashboard: Overview, Sales, Customers, Products, Regions
- [ ] One-page executive memo with quantified recommendations
- [ ] Data-flow diagram

## Success metrics

- Revenue, gross profit, margin, AOV, growth
- Revenue and margin by region / product / customer segment
- Estimated € impact of each recommendation

## Planned structure

```text
data/{raw,processed}  sql/  notebooks/  dashboard/  docs/
```

## Roadmap

- [x] Scope and README
- [ ] Data collection / generation
- [ ] Core implementation
- [ ] Evaluation and business-impact estimate
- [ ] Demo, write-up and interview notes

---

Part of my **Data & AI × Business Consulting** portfolio, a 16-week sprint of 8 projects going from data and BI to ML, GenAI, agents, automation and AI strategy. See all projects on my [GitHub profile](https://github.com/Amine-Charrou).

*Amine Charrou · Final-year Data Science & AI engineering student, ENSA Agadir · [LinkedIn](https://www.linkedin.com/in/amine-charrou/)*
