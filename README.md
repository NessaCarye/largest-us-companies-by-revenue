# Analysis of the Largest Companies in the USA by Revenue (2025)

**Description**  
This project explores the 100 largest U.S. companies by revenue (2025). It contains data cleaning (Python), cleaned CSVs, and a Power BI dashboard with visualizations such as top companies by revenue, industry revenue share, average revenue growth, and more.

**Contents**
- `data/` — cleaned CSV files used in analysis (companies.csv, optional summaries).
- `notebooks/` — Jupyter notebook `data_cleaning.ipynb` with web-scraping and cleaning steps.
- `powerbi/` — Power BI report `largest_companies_dashboard.pbix`.
- `scripts/` — optional Python scripts for automated cleaning.

**Key visuals**
- Top 5 companies by revenue (bar chart)
- Revenue share by industry (table / pie)
- Average revenue growth by industry (bar chart)
- Total revenue (summary card / pie)

   ```bash
   # Requirements: Python 3.8+, pandas, requests, beautifulsoup4
   pip install -r requirements.txt
   python scripts/clean_data.py


