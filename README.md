# Atmospheric Carbon Dioxide & Methane Analysis Using NOAA Datasets

This repository contains a complete analytical workflow for studying long‑term atmospheric greenhouse gas trends using publicly available datasets from the **NOAA** atmospheric monitoring programs. The project focuses on:

- **Carbon dioxide ($CO_2$)** — analyzed using **statistical time‑series models**
- **Methane ($CH_4$)** — analyzed using **machine‑learning forecasting methods**

## Repository structure

```text
├── data/               # Raw NOAA datasets for CO2 and CH4
├── time_series/        # Statistical time-series analysis of CO2
└── machine_learning/   # Machine-learning analysis of CH4
```
- `data/` – Contains the NOAA datasets used in the analyses
- `time_series/` - Has Jupyter notebook for $CO_2$ analysis using classical statistical time‑series methods.
- `machine_learning/` - Has Jupyter notebook for $CH_4$ analysis using machine‑learning models.

## Related Articles (Read More Detailed Discussion on My Website)

Full methodological discussion is provided inside the notebook markdown cells. You can also read the related articles on my website. This README provides only a high‑level overview of the repository!

- [Greenhouse Gas Modeling: Carbon Dioxide Analysis Using Statistical Time-Series Methods and NOAA Mauna Loa Data](https://paulmbaru.com/blog/articles/noaa-mauna-loa-co2-time-series-analysis.html)  
- [Atmospheric Methane Forecasting Using Machine Learning Models and NOAA Global Marine Data](https://paulmbaru.com/blog/articles/noaa-global-methane-machine-learning-forecasting.html)

## Requirements

The notebooks use standard scientific Python libraries:

```python
- pandas  
- numpy  
- matplotlib  
- seaborn  
- statsmodels  
- scikit-learn  
- tensorflow  
```
