# Machine Learning — Rental Price Prediction Hackathon

Hackathon notebook from the M.Tech Data Science & AI programme at PES University (Machine Learning 1).

`ML_Hackathon(rentalHouse_prediction).ipynb` predicts house rent from listing features joined with area-level average
rent and distance-from-city-centre tables, using a scikit-learn `Pipeline` (one-hot encoding via `ColumnTransformer`)
and a `RandomForestRegressor`, evaluated with mean squared error on a held-out split.

The hackathon datasets (train, test, average rent, distance from city centre) are not included; the notebook reads
them from Google Drive.

**Stack:** Python, pandas, NumPy, scikit-learn.
