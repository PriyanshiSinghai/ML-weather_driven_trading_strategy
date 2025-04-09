# ML-Augmented Weather-Driven Gas Trading Strategy

This project integrates deep learning-based weather forecasts with a natural gas trading strategy. Using a hybrid **LSTM** model to predict 2m surface temperature, we generate **Heating Degree Day (HDD)** anomalies and create rule-based trading signals to simulate gas trades (Henry Hub). The strategy mimics real-world workflows at hedge funds and energy trading desks, using meteorology as an alpha-generating input.

---

## 📌 Project Objectives

- Forecast regional temperatures using reanalysis and forecast weather data.
- Convert temperature forecasts into demand metrics like **HDD/CDD**.
- Develop rule-based and ML-enhanced gas trading strategies.
- Backtest performance using historical Henry Hub spot prices.
- Evaluate and compare strategies built on:
  - Raw ECMWF forecasts
  - AI-enhanced (LSTM) forecasts

---

## 🛠️ Tech Stack

| Category         | Tools / Libraries                                       |
|------------------|----------------------------------------------------------|
| Data Access      | `cdsapi`, `xarray`, `netCDF4`, `pandas`                  |
| ML Modeling      | `PyTorch`, `scikit-learn`, `NumPy`, `Matplotlib`         |
| Trading & Backtest | `bt`, `QuantStats`, `yfinance`, `pandas`               |
| Visualization    | `matplotlib`, `seaborn`, `plotly`                        |

---

## 📦 Directory Structure
