# Costa Rican Household Poverty Level Prediction

## Goal
Identify which households have the highest need for social welfare assistance.

## Data
See `data/` for the datasets.

## Feature descriptions
See `data_description.md` for the labels and their meanings.

## Exploratory Data Analysis (EDA)
See `eda.ipynb` for exploratory data analysis and nice plots.

## Model training
See `train.ipynb` for the code for training the model(s).

### Outline of the training
1. Preprocessing
    1. Deal with mislabeled features, like *dependency*.
    2. Deal with missing data (there is quite a lot).
    3. Feature engineering.
    4. Feature encoding.
2. Training
    1. Select a model.
    2. Search for the best hyperparams.
    3. Test trained model against other types of models.
