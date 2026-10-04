# Retail Performance Command Center

> From raw transactions to the five decisions management should make next.

![status](https://img.shields.io/badge/status-planned-lightgrey) ![phase](https://img.shields.io/badge/sprint-Weeks%201--2-blue)

**Category:** BI & Analytics · **Domain:** Retail · **Stack:** SQL · Python · Power BI · Excel

Project 01/08 of my *Data & AI × Business Consulting* portfolio. 🚧 **Design stage, no implementation yet.**

## Overview

An end-to-end analytics project that turns a retail company's raw sales data into one trusted view of performance. It cleans and models the data in SQL, validates it in Python, and delivers a five-page Power BI dashboard (overview, sales, customers, products, regions) plus a short executive memo with quantified recommendations.

## Business problem

A retail company has large volumes of transaction data, but management has no single, trusted view of revenue, profitability, customers, products and regions.

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

## Status

- [x] Scope and README
- [ ] Data
- [ ] Implementation
- [ ] Evaluation & business impact
- [ ] Demo and write-up

---

*Author: Amine Charrou · Final-year Data Science & AI engineering student, ENSA Agadir*
