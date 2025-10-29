# Forecasting Inbound Tourist Demand in Thailand: Assessing Recurrent Neural Networks

This project applies Recurrent Neural Networks (RNN) to forecast inbound tourist demand in Thailand and assess their effectiveness against traditional statistical models.

## Project Overview

The project aims to:

- Model and forecast inbound tourist arrivals using RNNs with stacked architectures.
- Evaluate the performance of different RNN units (Simple RNN, LSTM, GRU) on limited datasets.
- Compare results against traditional statistical models.
- Provide reproducible code and visualizations for analysis and insights.

## Datasets

All datasets are stored in the `data` folder:

- `thai_inbound_tourists.csv` – Monthly inbound tourist arrivals for Thailand collected from the Bank of Thailand [here](https://app.bot.or.th/BTWS_STAT/statistics/ReportPage.aspx?reportID=875&language=eng).

## Files Included

- `notebooks/thailand-tourism-univariate-forecasting-rnn.ipynb` – Jupyter notebook.
- `reports/thailand-tourism-univariate-forecasting-rnn.html` – Static HTML report.
- `figures` - Figure used in the report.
- `requirements.txt` – Python dependencies for replicating the analysis.
- `LICENSE.md` – Project licensing information.

## Notebook Structure

1. **Data Preprocessing:** Handling seasonality, outliers and normalization.
2. **Modeling:** Building and training RNN architectures (Simple RNN, LSTM, GRU).
3. **Evaluation:** Forecasting accuracy metrics, visualization and comparison against baseline models.
4. **Discussion:** Interpretation of results, limitations and future directions.

## System Requirements

- Python 3.8+
- OS-independent (tested on macOS, reproducible on Windows/Linux)
- Recommended: Jupyter Notebook or JupyterLab

## How to View the Report

Open `reports/thailand-tourism-univariate-forecasting-rnn.html` in a web browser to explore the methodology, results and insights.

## Reference

If you use or cite this work, please reference:

Grassi, S. (2025). *Forecasting of Inbound Tourist Demand in Thailand: Assessing Recurrent Neural Networks*. ResearchGate. DOI: 10.13140/RG.2.2.19998.80967 (https://www.researchgate.net/publication/370123456_Forecasting_of_Inbound_Tourist_Demand_in_Thailand_Assessing_Recurrent_Neural_Networks)
