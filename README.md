# Prediction of the number of days of hospitalization

## Features

* fin_type - Payment source
* admission_date - Date of admission to the hospital
* height - Height
* weight - Weight
* age - Age
* gender - Gender
* hosp_3 - Hospitalized for this disease this year
* hosp_procedure - Hospitalization procedure
* hosp_method - Method of admission (delivery)
* purpose - Purpose of admission
* channel - Channel of receipt
* diagnosis_main - Main diagnosis
* diagnosis_concom - Concomitant diagnosis
* hosp_days - Days of hospitalization (target variable)

## Model Evaluation Metric

* Coefficient of determination (R^2)

## Used machine learning model

* [CatBoostRegressor](https://catboost.ai/docs/concepts/python-reference_catboostregressor.html)