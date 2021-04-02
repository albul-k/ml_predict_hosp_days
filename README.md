# The number of days in hospital

## Features

* fin_type - Payment source
* admission_date - Date of admission to the hospital
* height - Height
* weight - Weight
* age - Age
* gender - Gender
* hosp - Hospitalized for this disease this year
* hosp_procedure - Hospitalization procedure
* hosp_method - Method of admission
* purpose - Purpose of admission
* channel - Channel of admission
* diagnosis_main - Main diagnosis
* diagnosis_concom - Concomitant diagnosis
* hosp_days - Days of hospitalization (target variable)

## Model Evaluation Metric

* Coefficient of determination (R^2)

## Used machine learning model

* [CatBoostRegressor](https://catboost.ai/docs/concepts/python-reference_catboostregressor.html)