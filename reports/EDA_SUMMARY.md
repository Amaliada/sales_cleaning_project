# EDA Summary

Artefacte generate automat din `03_eda.ipynb`.

## KPIs

- **Valoare Totală**: 77,680.84
- **Nr Tranzacții Unice**: 675
- **Nr Linii**: 683
- **Ticket Mediu Pe Tranzacție**: 115.08
- **Preț Mediu**: 30.80
- **Cantitate Medie Pe Linie**: 3.62
- **Clienți Unici**: 234
- **Produse Unice**: 60
- **Magazine Unice**: 5

## Topuri

- **Top 10 produse**: vezi `reports/top10_products.png` și `reports/top_products.csv`.
- **Top 10 magazine**: vezi `reports/top10_stores.png` și `reports/sales_by_store.csv`.
- **Top 10 orașe**: vezi `reports/top10_cities.png` și `reports/sales_by_city.csv`.

## Trenduri

- Evoluție zilnică: `reports/daily_sales.png`.
- Evoluție săptămânală: `reports/weekly_sales.png`.

## Promoții

- **Acoperire promo**: 0.0% din linii.
- **Lift cantitate (Promo vs non-Promo)**: nan%
- **Lift valoare/linie (Promo vs non-Promo)**: nan%
- **Δ preț mediu (Promo vs non-Promo)**: nan%

## Outlieri (IQR)

- effective_price: 0 rânduri potențial outlier
- quantity: 0 rânduri potențial outlier

## Reproducere

1. Rulează `01_collect_merge.ipynb` → `02_cleaning.ipynb` → `03_eda.ipynb`.
2. Artefactele apar în folderul `reports/` (CSV + PNG + acest rezumat).