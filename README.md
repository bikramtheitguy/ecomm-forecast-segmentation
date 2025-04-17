# E‑Commerce Forecast & Segmentation Pipeline

**Project Overview**\
An end‑to‑end demonstration of e‑commerce analytics:

1. Ingest raw transaction data
2. Clean & handle nulls/outliers
3. Engineer time‑based features (lags & recency)
4. Segment customers with K‑Means
5. Forecast 30‑day sales using Prophet

---

## Tech Stack & Prereqs

- **Python** 3.8+
- **Libraries:** Pandas, scikit‑learn, Prophet, Jupyter Notebooks
- **Install dependencies:**
  ```bash
  pip install -r requirements.txt
  ```

---

## Usage Instructions


git clone https://github.com/bikramtheitguy/ecomm-forecast-segmentation.git
cd ecomm-forecast-segmentation
pip install -r requirements.txt
# Open and execute notebooks in order:
#    01_data_ingestion.ipynb
#    02_data_cleaning.ipynb
#    03_feature_engineering.ipynb
#    04_clustering.ipynb
#    05_forecasting.ipynb
```

---

## Notebooks Overview

| Notebook                       | Purpose                                  |
| ------------------------------ | ---------------------------------------- |
| `01_data_ingestion.ipynb`      | Load raw CSVs into Pandas                |
| `02_data_cleaning.ipynb`       | Handle nulls & detect outliers           |
| `03_feature_engineering.ipynb` | Create lag features & compute recency    |
| `04_clustering.ipynb`          | Segment customers via K‑Means clustering |
| `05_forecasting.ipynb`         | Fit Prophet model & forecast daily sales |

---

## Output Artifacts

All generated CSVs live under `data/processed/`:

- `cleaned_transactions.csv`
- `features.csv`
- `customer_segments.csv`
- `forecast.csv`

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

Bikram The IT Guy • [LinkedIn](www.linkedin.com/in/bikram-keshari-samal-3975222a5) • [GitHub](https://github.com/bikramtheitguy)


Usage Instructions


Copy code
git clone https://github.com/bikramtheitguy/ecomm-forecast-segmentation.git
cd ecomm-forecast-segmentation
pip install -r requirements.txt
# Run notebooks in order:
#    01 → 02 → 03 → 04 → 05
Notebook Summaries

01_data_ingestion.ipynb – Load raw transactions

02_data_cleaning.ipynb – Handle nulls & outliers

03_feature_engineering.ipynb – Create lag & recency features

04_clustering.ipynb – Segment customers via K‑Means

05_forecasting.ipynb – Forecast daily sales with Prophet

Output Artifacts
List the CSVs in data/processed/:

cleaned_transactions.csv

features.csv

customer_segments.csv

forecast.csv