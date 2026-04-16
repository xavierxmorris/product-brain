# NPS Drivers Dashboard

> **Prototype** — stakeholder-facing summary of the updated Q4 2025 NPS drivers notebook

## What it demonstrates

- A concise executive readout of the updated NPS analysis (`n=352`)
- The strongest quantitative drivers of NPS, led by overall satisfaction and checkout
- Why **mobile web** should be separated from app in stakeholder reporting
- How tenure and membership tier amplify NPS outcomes

## Source files

- [analysis/notebooks/customer-nps-analysis-q4-2025.ipynb](../../analysis/notebooks/customer-nps-analysis-q4-2025.ipynb)
- [insights/nps-drivers-q4.md](../../insights/nps-drivers-q4.md)

## Key findings reflected in the prototype

- Overall NPS is **13.35** with **40.06% promoters** and **26.70% detractors**
- Strongest correlations: overall satisfaction (**0.9642**), checkout (**0.9234**), returns (**0.8925**), search (**0.8465**)
- Mobile web is the outlier: **5.400 NPS** and **2.324 checkout satisfaction**
- Mobile-web respondents skew early-tenure, but the channel still underperforms within the Established cohort

## Tech stack

- Single-file HTML
- Tailwind CSS via CDN
- Alpine.js
- Chart.js

## Notes

- Includes a clear prototype banner per the repo prototype guidelines
- Designed with the Contoso dark design system used across existing demos
