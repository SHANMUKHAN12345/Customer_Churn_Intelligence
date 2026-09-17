# Customer Churn & Retention Intelligence

An end-to-end analytics project designed to analyze customer churn, identify retention patterns, measure revenue exposure, and segment customers based on churn risk.

The project demonstrates a complete data analytics workflow using Python, PostgreSQL, SQL, and Power BI.

---

## Project Overview

Customer churn is an important business problem because losing customers can directly affect recurring revenue and long-term growth.

This project analyzes customer information across:

- Customer demographics
- Subscription plans
- Contract types
- Tenure
- Auto-renewal behavior
- Monthly activity
- Payments
- Support interactions

The solution transforms raw customer data into an interactive Power BI intelligence dashboard that enables users to explore churn patterns, customer engagement, support behavior, and customer risk.

> **Note:** The dataset used in this portfolio project is synthetically generated for analytical and demonstration purposes.

---

## Objectives

- Analyze overall customer churn and retention
- Identify churn patterns across subscription plans
- Compare churn across contract types
- Analyze the relationship between auto-renewal and churn
- Study churn patterns across customer tenure
- Compare customer engagement between active and churned customers
- Analyze support activity and satisfaction
- Estimate monthly revenue associated with churned customers
- Segment customers into risk categories
- Build an interactive business intelligence dashboard

---

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data generation, cleaning and EDA |
| Pandas | Data manipulation and preprocessing |
| Matplotlib | Exploratory data visualization |
| PostgreSQL | Relational database and data storage |
| SQL | Data analysis and analytical views |
| Power BI | Interactive dashboard and visualization |
| DAX | KPI and analytical measures |
| pgAdmin | PostgreSQL database management |

---

## Project Architecture

```text
                ┌──────────────────────┐
                │   Synthetic Dataset  │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │       Python         │
                │ Data Cleaning & EDA  │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │     PostgreSQL       │
                │ Relational Database  │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │    SQL Analytics     │
                │ Views & Risk Logic   │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │      Power BI        │
                │ Dashboard & DAX KPI  │
                └──────────────────────┘

## Power BI Dashboard

### Executive Overview

![Executive Overview](documentation/executive-overview.png)

### Engagement & Support

![Engagement & Support](documentation/engagement-support.png)

### Retention & Risk

![Retention & Risk](documentation/retention-risk.png)

### Customer Detail

![Customer Detail](documentation/customer-detail.png)
