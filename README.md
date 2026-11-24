# NBA Point-in-Time Team Features — Free Sample

Leak-free, pre-game team features for NBA totals modeling: every row is computed only from games played BEFORE tip-off, so models trained on it do not leak future information.

## Free sample
79 games from the 2026-27 season (56 features per game) are published as a free dataset on Kaggle:
https://www.kaggle.com/datasets/kmdspark5/nba-point-in-time-team-features-sample-2026-27

A runnable demo notebook (Gradient Boosting baseline, honest metrics):
https://www.kaggle.com/code/kmdspark5/predicting-nba-totals-with-leak-free-features

## Full dataset
4,372 games, 2022-23 through 2026-27, with data dictionary and example notebook:
https://kmdspark5.gumroad.com/l/pisdro

Also available: a 3-season walk-forward backtest of model predictions vs closing lines (3,216 games):
https://kmdspark5.gumroad.com/l/vkoul

Use code LAUNCH25 for 25% off until November 30, 2026.

## Honest benchmark
Default Gradient Boosting trained on the full dataset scores RMSE 19.56 / MAE 15.56 / 39.2% within ±10 points on the 2025-26 season. This is research material, not betting advice.
