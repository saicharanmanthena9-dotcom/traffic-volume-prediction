# Traffic Volume Prediction

A machine learning project that predicts hourly traffic volume using time and weather features.

## Dataset
Metro Interstate Traffic Volume dataset (Kaggle / UCI).
[Change this if you used a different dataset]

## Tools
Python, Pandas, NumPy, Matplotlib, Scikit-Learn, Google Colab

## Steps
1. Loaded and cleaned the data with Pandas
2. Created features: hour, weekday, month, temperature in Celsius and weather type
3. Filled missing values and split the data into train and test sets
4. Trained Linear Regression and Random Forest models
5. Compared the models using MAE and R² score

## Results
| Model | MAE | R² |
|---|---|---|
| Linear Regression | [1589.9] | [0.17] |
| Random Forest | [251.9] | [0.947] |

## Findings
- Busiest hours: [for example, 7-8 AM and 4-5 PM]
- Best model: [Random Forest or Linear Regression]

## Notebook
traffic_volume_prediction.ipynb
