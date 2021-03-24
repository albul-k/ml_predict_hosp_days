# Prediction of the number of days of hospitalization

## Feature Description

* fin_type - Payment source
* admission_date - Date of admission to the hospital
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

* [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html?highlight=random%20forest#)