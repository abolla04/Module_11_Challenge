# Module_11_Challenge

This analysis focuses on MercadoLibre's financial and user data to predict online search traffic and how it translates to the company's financial sucess.  The analysis was created in Google Colab and utilizes
three csv files - google_hourly_search_trends, mercado_daily_revenue and mercado_stock_price.

The first step of the analysis detects patterns in hourly Google search traffic.
The next step focuses on seasonaility in the search traffic data.
The third step then compares the search traffic with patterns in the stock price.
The fourth step then creates a time series model using Prophet.
The final step forecasts the revenue using time series models.

---

## Technologies

This analysis utilized python 3.7 and the following installs:

    !pip install pystan
    !pip install fbprophet
    !pip install hvplot
    !pip install holoviews

---

## Installation Guide

To run the analysis, install the following dependencies:

    import pandas as pd
    import numpy as np
    import holoviews as hv
    from fbprophet import Prophet
    import hvplot.pandas
    import datetime as dt
    from pathlib import Path
    %matplotlib inline

---

## Usage

To view the analysis, open the forecasting_net_prophet.ipynb from the repository.

---

##  Contributors

Brough to you by Abolla, Growth Analyst at MercadoLibre

---

## License

MIT

---
