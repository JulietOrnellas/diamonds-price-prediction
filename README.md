# Diamonds Price Prediction 💎

This repository contains an end‑to‑end regression analysis of the classic **`seaborn` diamonds** dataset. The project showcases core data‑science skills—exploratory analysis, feature engineering, ordinary‑least‑squares modeling, metric comparison, and clear visualization—making it a strong portfolio piece.

---

## Project Overview
The objectives of this analysis are to:

* **Investigate** relationships between diamond price and key attributes (carat, depth, and table).  
* **Build** two OLS regression models:  
  * **Model A:** `price ~ carat`  
  * **Model B:** `price ~ carat + depth + table`  
* **Compare** performance using MAE and RMSE.  
* **Visualize** correlations and model fit to convey insights.

---

## Features
| Step | Description |
|------|-------------|
| **Data Loading** | Import the built‑in `diamonds` dataset from `seaborn`. |
| **Exploratory Analysis** | Compute correlations and drop highly collinear dimensions (`x y z`). |
| **Modeling** | Fit simple and multi‑feature OLS models with `statsmodels`. |
| **Evaluation** | Calculate MAE and RMSE to quantify improvement. |
| **Visualization** | Bar chart comparing error metrics and scatterplots with regression lines. |

---

## Requirements
Install the following libraries before running the notebook:

```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn
