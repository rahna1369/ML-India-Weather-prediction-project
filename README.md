# ML-India-Weather-prediction-project

This project predicts weather conditions using supervised machine learning.  
The main goal is to predict average temperature, rainfall amount, and rain/no-rain status using historical weather data.

---

## Project Overview

This project uses machine learning models to predict:

- Average temperature
- Rainfall amount in millimeters
- Rain / No Rain status

The project focuses on supervised learning because the dataset contains target values such as temperature and rainfall.

---

## Dataset

The dataset contains historical weather records of Indian cities.

Main columns used in this project:

- `date`
- `city`
- `tavg` - average temperature
- `tmin` - minimum temperature
- `tmax` - maximum temperature
- `prcp` - precipitation / rainfall
- `pres` - atmospheric pressure

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Joblib

---

## Project Steps

1. Data loading
2. Data inspection
3. Exploratory Data Analysis
4. Missing value handling
5. Outlier handling
6. Log transformation
7. Feature encoding
8. Feature selection
9. Train-test split
10. Feature scaling
11. Model training
12. Model evaluation
13. 2026 weather prediction
14. Model saving
15. Streamlit deployment

---

## Machine Learning Models Used

### Regression Models

Used to predict numerical values such as temperature and rainfall amount.

- Linear Regression
- Random Forest Regressor

### Classification Models

Used to predict whether rainfall will occur or not.

- Logistic Regression
- Random Forest Classifier

---

## Model Evaluation

Regression models were evaluated using:

- MAE
- RMSE
- R2 Score

Classification models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

---

## Output

The project predicts:

- 2026 average temperature
- 2026 rainfall amount
- Rain / No Rain status

Example output:

- City: Kochi
- Month: June
- Predicted Rainfall: rainfall amount in mm
- Rain Status: Rain / No Rain

---

## Deployment

The project can be deployed using Streamlit.

The Streamlit app allows users to select:

- City
- Month
- Year

Then the app predicts:

- Average temperature
- Rainfall amount
- Rain / No Rain status

---

## Files in This Repository

- `india_weather.ipynb` - full project notebook
- `app.py` - Streamlit app file
- `requirements.txt` - required Python libraries
- `cleaned_weather_dataset.csv` - cleaned dataset
- `temperature_model.pkl` - saved temperature prediction model
- `rainfall_model.pkl` - saved rainfall prediction model
- `rain_classifier_model.pkl` - saved rain/no-rain classification model
- `city_encoder.pkl` - saved city encoder

---

## Conclusion

This project successfully applies supervised machine learning techniques to predict weather conditions. Regression models are used for temperature and rainfall amount prediction, while classification models are used for rain/no-rain prediction. The final model can be deployed as a web application using Streamlit.
