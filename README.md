# DSA2050 Week 1 — Retail Analysis

**Student name:** Tamara Mwakisha
**Student ID:** - 660146

## Project objective
Use a small retail transaction dataset to frame a business question, summarize sales with three descriptive KPIs, visualize two sales patterns, and provide a reproducible, decision-oriented first look.

## Files
- `retail.csv` — source dataset
- `week1_analysis.ipynb` — runnable notebook with inspection, KPI calculations, labelled plots, interpretations, and conclusion
- `decision_brief.md` — one-page decision brief
- `requirements.txt` — Python dependencies
- `outputs/` — rendered plot images from the notebook

## Three KPIs
1. **Total revenue:** KES 3,206,450 across the observed orders.
2. **Number of transactions:** 300 unique order IDs.
3. **Average transaction value:** KES 10,688.17 per order (total revenue divided by unique orders).

## Two key findings
- Revenue was highest in **2026-03** (KES 1,367,650) and lowest in **2026-02** (KES 909,900); the highest month was 50.3% above the lowest.
- **Kisumu** had the largest aggregate regional revenue (KES 878,050) in this sample.

These are descriptive results for this dataset and period, not evidence of causes or a forecast.

## Run the notebook
From the repository root, install the listed dependencies and launch Jupyter:

```bash
python -m pip install -r requirements.txt
jupyter notebook week1_analysis.ipynb
```

The notebook reads `retail.csv` using a relative path from the repository root. Restart the kernel and run all cells from top to bottom to reproduce the outputs.
