# sales_cleaning_project
cleaning and analyze eda

## How to reproduce

1. Create & activate venv, install deps:
   - `python -m venv .venv`
   - `.\.venv\Scripts\activate`
   - `pip install -r requirements.txt`  (sau pachetele din README)

2. Run notebooks in order:
   - `notebooks/01_collect_merge.ipynb`
   - `notebooks/02_cleaning.ipynb`
   - `notebooks/03_eda.ipynb`

3. Outputs:
   - Clean data: `data/processed/sales_clean.parquet`
   - Reports: `reports/EDA_SUMMARY.md` + CSV/PNG în `reports/`

