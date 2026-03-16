# Beyond Extremes: Asymmetric Coupling Strength and Sensitivity of Global Vegetation Productivity to Precipitation
The code is written in Python and implemented in a Jupyter Notebook format (Analyse and drawing code.ipynb), providing a fully reproducible pipeline for quantifying the asymmetric response of vegetation productivity to precipitation anomalies across global dryland and humid regions.

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](Analyse%20and%20drawing%20code.ipynb)
## 📌 Overview
We propose three novel Asymmetric Indices (AIs) to characterize the differential sensitivity of vegetation to precipitation under dry vs. wet conditions:

### AIₛ: Based on slope differences of linear fits

### AIᵣ: Based on correlation coefficient differences

### AIₑ: Based on extreme-value deviations

These indices are computed globally using multiple long-term satellite-derived and climate datasets (NDVI, LAI, GPP, precipitation) at 0.25° and 0.5° spatial resolutions.

## 🧰 Features
Data preprocessing and resampling (NDVI, LAI, CRU, TerraClimate)

Pixel-wise and neighborhood-based (8-neighbor, 24-neighbor) AI calculation

Masking by aridity zones and vegetation types (IGBP classification)

Statistical analyses: linear regression, significance testing, trend detection

High-resolution visualizations:

Global AI maps

Gradient plots along aridity gradients

Vegetation-type pie charts

Time-window trend analysis (20, 25, 30 years)

Pairwise comparisons across data sources and resolutions

## 📁 Repository Structure

├── Analyse and drawing code.ipynb   # Main Jupyter notebook with all analysis and plotting

├── README.md                         # This file

## 🛠️ Requirements
The code requires Python 3.8+ and the following libraries:

numpy, scipy, pandas

matplotlib, seaborn

rasterio, rioxarray, xarray, netCDF4

geopandas, gdal

statsmodels, scikit-learn

tqdm, pyhdf, h5py
