# FUTURE_DS_01 — Business Sales Dashboard (E-commerce)

**Intern:** Your Name  
**Track:** Data Science & Analytics — Future Interns (Task 1)

## Overview
Interactive sales dashboard that analyzes e-commerce transactions to surface:
- Best-selling products
- Monthly/seasonal sales peaks
- High-revenue categories & regions
- Customer behavioral metrics

## Repo structure
FUTURE_DS_01/
├─ data/
│  ├─ raw/                # original CSV/Excel (do not modify)
│  └─ processed/          # cleaned CSVs (outputs)
├─ notebooks/             # starter notebook (cleaning + EDA)
├─ powerbi/               # dashboard.pbix
├─ reports/               # screenshots & exported PDFs
├─ images/                # saved PNG charts
├─ README.md
└─ requirements.txt

## How to reproduce
1. Put original dataset in `data/raw/orders.csv`.
2. Open `notebooks/01_data_cleaning_and_eda.ipynb` and run cells (or run in Colab).
3. Use `data/processed/orders_clean.csv` as the source in Power BI Desktop.
4. Open `powerbi/dashboard.pbix`, refresh data, build visuals.

## Key files & deliverables
- `data/processed/orders_clean.csv` — cleaned dataset
- `powerbi/dashboard.pbix` — final report
- `reports/report.pdf` — 1-page executive summary (insights + recommendations)
- `images/` — charts/screenshots used in the report

## Quick insights (example)
- Top category by revenue: **[Category X]**
- Peak month: **[Month Y]**
- Recommendation: **[2 actionable points]**

## Notes
- If your dataset uses different column names, update the notebook mapping at the top.
- Keep the repo public; provide the link in the task submission form.

## Author
M.ShreeNidhii — Intern at Future Interns
