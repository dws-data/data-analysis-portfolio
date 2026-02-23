# Premier League Card Prediction

## Overview
This project predicts the number of yellow and red cards in Premier League football matches using statistical modeling. The goal is to accurately forecast match disciplinary cards using time-weighted team profiles and walk-forward validation.

## Tools Used
* Python (Pandas, NumPy, SciPy)
* Matplotlib
* Jupyter Notebook / VS Code

## Key Steps
* Data cleaning and standardization (team/referee names)
* Time-weighted profile construction (exponential decay)
* Learned mixing weights (correlation-based optimization)
* Walk-forward validation (no data leakage)
* Poisson probability framework
* Model evaluation and performance tracking

## Models
* **Prototype (Phase 1)**: Season-level averages with fixed 50/50 mixing weights
* **Production (Phase 2)**: Match-level data with learned mixing weights

## Key Results
* Achieved MAE of 1.67 cards per match
* 66.5% of predictions within 2 cards of actual outcome
* Discovered away teams are more context-dependent (55% influenced by home opponent vs 45% own tendency)
* Removing referee scaling improved all metrics (simpler model performed better)

## Data
Data files are not included in this repository. The model uses match-level data (5 seasons, 2021-2026), team statistics, and referee data sourced from football-data.co.uk, thestatsdontlie.com, and whoscored.com.

## Next steps 
- Automation
