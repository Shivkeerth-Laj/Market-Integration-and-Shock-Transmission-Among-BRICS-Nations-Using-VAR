# Market Integration and Shock Transmission Among BRICS Nations Using VAR

## Overview
This project investigates how market integration among the BRICS nations (Brazil, India, China) impacts stock market efficiency and the transmission of economic shocks. Built as part of the ECON339 – Applied Financial Modelling course under the supervision of Dr. Kashif Saleem.

## Key Objectives
- Assess market efficiency using ARMA models.
- Analyze short-run and long-run financial relationships using VAR, VECM, and Johansen Cointegration Test.
- Examine the shock transmission effect using Impulse Response Functions and Granger Causality Tests.

## Tools & Techniques
- Software: EViews 12  
- Models Used:  
  - ARMA (for market efficiency)  
  - VAR (for short-run market integration)  
  - VECM & Johansen Cointegration Test (for long-run relationships)

## Methodology
- Downloaded weekly stock index data (IBOVESPA, NSE, SSE) from Capital IQ for the last 5 years.
- Transformed data using `dlog` to obtain return series.
- Conducted:
  - Stationarity tests (ADF & KPSS)
  - Lag selection using AIC & BIC
  - Impulse Response and Variance Decomposition
  - Granger causality analysis
  - Johansen Cointegration test

## Results Summary
- Brazil showed short-term inefficiencies via ARMA (3,1).
- China demonstrated market efficiency.
- India showed predictive power in ARMA (2,3).
- VAR Results: China’s market Granger-caused Brazil’s, but not India’s.
- VECM revealed long-run cointegration.
- Variance Decomposition: Chinese market influenced 60–70% of variance in India and Brazil.

## KPI Achieved
- Validated all models with over 90% significance.
- Generated six visual dashboards explaining market interdependence and policy risk exposure.

## Project Files
- `/data/`: Raw and transformed stock data
- `/models/`: EViews model outputs and lag selection tables
- `/visuals/`: Graphs for IRF, variance decomposition, and cointegration results
- `report.pdf`: Final academic report submission

## Insight for Investors
- Diversification across BRICS is useful, but markets respond differently to shocks.
- China plays a dominant role in regional volatility and investor strategy.


**Author**: Shivkeerth Laj  
**Course**: ECON339 – Applied Financial Modelling  
**Instructor**: Dr. Kashif Saleem  and Sherwin Fernandes
**University**: University of Wollongong Dubai
