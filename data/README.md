# Dataset Information

## Source & Download Instructions

The dataset for this project comes from the Kaggle competition:
**[Recruit Restaurant Visitor Forecasting](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting/data)**

### How to Download:
1. Visit the competition data page: https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting/data
2. Accept the competition rules to enable downloads.
3. Download the data files (or use the Kaggle CLI: `kaggle competitions download -c recruit-restaurant-visitor-forecasting`).
4. Extract the CSV files directly into this `data/` directory.

---

## Required CSV Files

The following CSV files belong in this `data/` folder:

| File Name | Description |
| :--- | :--- |
| `air_visit_data.csv` | Historical visitor numbers for Air restaurants (primary target variable for forecasting). |
| `air_reserve.csv` | Reservations made through the Air system. |
| `air_store_info.csv` | Metadata for Air restaurants (genre name, area name, latitude, longitude). |
| `date_info.csv` | Calendar information including day of the week and Japanese public holidays. |
| `hpg_reserve.csv` | Reservations made through the HPG system. |
| `hpg_store_info.csv` | Metadata for HPG restaurants (genre name, area name, latitude, longitude). |
| `store_id_relation.csv` | Relational mapping linking `air_store_id` to `hpg_store_id`. |
| `sample_submission.csv` | Kaggle submission format specifying target stores and forecast dates. |

> **Note:** All `.csv` files in this directory are excluded from Git version control via `.gitignore`.
