# Stock-Bond Correlation Regimes Across Crisis Types

**Author:** Deshna Kankaria  
**Course:** Quant Mentorship Final Project, April 2026

## Overview

This project investigates whether the type of macroeconomic shock 
(growth-driven vs. inflation-driven) explains the 2022 breakdown of the 
stock-bond correlation. Using 21 years of daily data, it tests three 
findings about regime persistence, the decoupling of volatility from 
correlation direction, and the weakening predictive power of the 
Treasury yield curve post-2022.

## Repository Contents

- `quant_final_project.ipynb` — main analysis notebook
- `Stock_Bond_Correlation_Report.pdf` — 3-page summary report
- `Stock_Bond_Correlation_Slide.pptx` — one-slide presentation  
- `data/prices_yahoo.csv` — daily close prices for SPY, TLT, 11 SPDR sector 
  ETFs, and VIX (2005-01-03 to 2026-04-13), pulled from Yahoo Finance
- `data/yield_spread_fred.csv` — daily 10Y-2Y Treasury yield spread, 
  pulled from FRED (series T10Y2Y)

## Running the Notebook

The notebook loads data from local CSVs (no API calls required). 
Required packages: pandas, numpy, matplotlib, seaborn, statsmodels, 
arch, scipy.

## References

Molenaar, R., Senechal, E., Swinkels, L., & Wang, Z. (2024). Empirical 
Evidence on the Stock-Bond Correlation. *Financial Analysts Journal*, 
80(2).
