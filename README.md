# Identifying Data-Driven Predictors of Electric Vehicle Sales in the Netherlands

This repository contains the code, datasets, and modeling attempts for my master's thesis on forecasting monthly electric vehicle (EV) sales in the Netherlands using public, macroeconomic, and behavioral data.

## Repository Structure


### Final Revision
Contains all the code used for the final modeling process.

- Extra explanation about the model is provided in my thesis logbook (see: `logboek`).

- **Revision.ipynb**  
  The main notebook where I iteratively built, tuned, and evaluated the final model.

- **Preprocessing.ipynb**  
  Scripts to load, clean, and merge all datasets used in the analysis.



## Datasets (CSV Files)

These files were used and referenced in the preprocessing and modeling notebooks:

| Filename | Description |
|----------|-------------|
| `TopTrends_EV_Zoektermen_NL_2007heden.csv` | Google Trends data for the  search terms most correlated with EV sales |
| `consumentenvertrouwen_2007_Merged.csv` | Macroeconomic indicators (e.g., Consumer Confidence Index) from CBS |
| `df_pompprijzen_Nieuwaggregatie.csv` | Aggregated monthly gas prices in the Netherlands |
| `df_wegvoertuigen_2007.csv` | Monthly EV sales data |
| `joined_trend_sales_All1.csv` | Final dataset used to train the XGBoost model (merged trends + sales) |
| `samengevoegde_trends.csv` | Raw Google Trends data for all keyword candidates |

## Notes

- The notebooks may be disorganized.

## AI Disclaimer

This project uses an ARIMAX model trained on publicly available datasets to forecast electric vehicle sales. While efforts were made to ensure data quality and model robustness, all predictions are subject to limitations inherent to the data and modeling assumptions. These outputs should not be used for high-stakes or commercial decisions without further validation.

Generative AI tools were occasionally consulted to assist with explanations, clarification, language refinement, code formatting, and the general formulation of ideas. All content was critically reviewed and edited to ensure academic integrity.

