# 🏦 Banking Risk Analytics

## Overview
End-to-end data analytics project on 100K+ banking customer 
records to identify loan default risk patterns.

## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- MySQL (CTEs, JOINs, Window Functions)
- Power BI (DAX Measures, Interactive Dashboard)

## Key Findings
- 22.5% overall default rate across 100K+ customers
- Low credit score (<650) is strongest default predictor
- Customers with 2+ credit problems default 3x more
- Home Mortgage holders = lowest default rate (48% of loans)
- Debt Consolidation = highest volume loan purpose

## Dashboard Preview
<img width="1119" height="635" alt="Screenshot 2026-04-28 163013" src="https://github.com/user-attachments/assets/dacbd233-c30a-44cd-8c4e-01077e87240a" />


## Project Structure
| File | Description |
|------|-------------|
| `banking_risk_eda.ipynb` | Full Python EDA notebook |
| `Banking_Risk_Analytics.pbix` | Power BI dashboard file |
| `credit_train.csv` | Dataset (100K+ records) |

## SQL Queries
- Overall default rate analysis
- Default rate by loan purpose
- Customer risk segmentation (CTE)
- Income group vs defaults
- Home ownership vs default rate
