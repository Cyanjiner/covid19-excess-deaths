# Cross-country Comparisons in Estimating COVID-19 Excess Deaths
This is a research project on estimating excess mortality during COVID-19 in four countries: US, UK, Brazil, and Russia. Excess deaths are calculated by taking the difference between reported deaths and expected deaths (forecasted number of deaths in the absence of pandemic), and an additional metric of P-score is computed for cross-country comparies.

The ARIMA (Autoregressive integrated moving average), GARCH (generalized autoregressive conditional heteroskedasticity), and VAR (Vector autoregression) models were fitted on historical data from 2015 to 2019 to get the expected mortality in 2020 and 2021. In addition, ARIMAX (Autoregressive Integrated Moving Average Exogenous Variable Models) and LSTM (Long Short-term Memory) models are also incorporated to account for variance in governmental resctrictions across countries.

The dataset used in this project comes from [the World Mortality Dataset](https://github.com/akarlinsky/world_mortality), which contains country-level data on deaths from all causes in 2015-2021 collected from various resources.

**Source code** in this research can be found in [excess-deaths.Rmd](https://github.com/Cyanjiner/covid19-excess-deaths/blob/main/excess-deaths.Rmd).

**Presentation Slides:**[JZ-Excess-Deaths.pdf](https://github.com/Cyanjiner/covid19-excess-deaths/blob/main/JZ-Excess-Deaths.pdf)
