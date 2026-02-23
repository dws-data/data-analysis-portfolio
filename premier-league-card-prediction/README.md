# Premier League Card Prediction

Predicts yellow and red cards in Premier League matches using weighted team profiles and Poisson regression.

**Results:** MAE: 1.67 cards | Log-Loss: 2.16 | 1,293 matches tested - NEEDS UPDATING

## Files
- `01_prototype_season_model.py` - Initial prototype with season-level data
- `02_match_level_model.py` - Production model with walk-forward validation

## Data
Data files are not included in this repository. The model uses:
- Match-level data (5 seasons, 2021-2026)
- Team statistics (home/away card averages)
- Referee data (career averages)

Data sourced from football-data.co.uk, thestatsdontlie.com, and whoscored.com

## Next steps 
- Automation
