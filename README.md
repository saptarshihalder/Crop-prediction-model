# Crop Prediction and Analysis

This project focuses on predicting crop prices and analyzing various factors affecting crop prices in different states in India. The analysis includes exploratory data analysis (EDA), model building using neural networks, random forest, and XGBoost, as well as visualizations of best and worst crops by state.

## Dataset

The dataset used for this project is obtained from [here](https://raw.githubusercontent.com/saptarshihalder/Crop-prediction-model/main/indiancrop_dataset.csv). It contains the following columns:
- `N_SOIL`: Nitrogen content in the soil
- `P_SOIL`: Phosphorus content in the soil
- `K_SOIL`: Potassium content in the soil
- `TEMPERATURE`: Temperature in Celsius
- `HUMIDITY`: Humidity percentage
- `ph`: pH value of the soil
- `RAINFALL`: Rainfall in mm
- `STATE`: State in India
- `CROP_PRICE`: Crop price
- `CROP`: Crop type

## Installation

To run the code, you need to have Python installed with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- tensorflow

You can install these libraries using `pip`:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow
