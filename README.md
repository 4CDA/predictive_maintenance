# Predictive Maintenance
Code base for Predictive Maintenance sample implementation. The original blog post can be found [here](link).
Analysis and prediction of turbofan degradation using popular regression models, including XGBoost, CatBoost and Random Forest.

## Usage
In your venv:
`pip install xgboost`
`pip install scikit-learn`
`pip install (other dependencies e.g. numpy, pandas, matplotlib)`

After downloading and opening the .ipynb file, ensure you modify the pd.read_csv() function so it points towards the location where you have stored the downloaded data.

## Dataset

NASA turbofan simulation data was used to develop the model. The data was collected by sensors in an effort to characterise fault evolution.

[Link to dataset](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan)

