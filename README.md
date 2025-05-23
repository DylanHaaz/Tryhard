# Identifying Data-Driven Predictors of Electric Vehicle Sales in the Netherlands

This repository contains the code, datasets, and modeling attempts for my master's thesis on forecasting monthly electric vehicle (EV) sales in the Netherlands using public, macroeconomic, and behavioral data.

## Repository Structure

### 70%/
Contains all the code used for the final modeling process.

- **Modelvergelijking.ipynb**  
  Early attempts to compare multiple models. No successful alternative to XGBoost was found here.

- **Preprocessing.ipynb**  
  Scripts to load, clean, and merge all datasets used in the analysis.

- **xgboost.ipynb**  
  The main notebook where I iteratively built, tuned, and evaluated the final XGBoost model.

## Datasets (CSV Files)

These files were used and referenced in the preprocessing and modeling notebooks:

| Filename | Description |
|----------|-------------|
| `TopTrends_EV_Zoektermen_NL_2007heden.csv` | Google Trends data for the 3 search terms most correlated with EV sales |
| `consumentenvertrouwen_2007_Merged.csv` | Macroeconomic indicators (e.g., Consumer Confidence Index) from CBS |
| `df_pompprijzen_Nieuwaggregatie.csv` | Aggregated monthly gas prices in the Netherlands |
| `df_wegvoertuigen_2007.csv` | Monthly EV sales data |
| `joined_trend_sales_All1.csv` | Final dataset used to train the XGBoost model (merged trends + sales) |
| `samengevoegde_trends.csv` | Raw Google Trends data for all keyword candidates |

## Notes

- The notebooks may be disorganized.
- Final code snippets and clean explanations are provided in my thesis logbook (see: `logboek`).
