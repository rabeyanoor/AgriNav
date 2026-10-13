# AgriNav

AgriNav is a crop advisory project built for the NASA Space Apps Challenge.
It trains machine learning models on NASA POWER climate data (rainfall, temperature, humidity, solar radiation, wind).
Two Random Forest models predict climate risk level and the most suitable crop for districts in Bangladesh.
Train with `python train_model.py --task risk` or `--task crop`, then run `python predict.py` for forecasts, risk maps and alerts.
