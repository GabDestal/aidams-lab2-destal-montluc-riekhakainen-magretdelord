# aidams-lab2-destal-montluc-riekhakainen-magretdelord

## Run the notebook

Use Python 3.10 or newer. From the repository folder, install the notebook's dependencies:

pip install pandas numpy openpyxl scikit-learn pandera mlflow optuna "optuna-integration[mlflow]" joblib jupyterlab ipykernel

or

```uv sync```

Run the notebook cells in order. The GIST workbook is included in `data/`; the Task 1.1 cell reads `data/Plant-level_data_Global_Iron_and_Steel_Tracker_June_2026_V1.xlsx`.

The packages are used for data handling (`pandas`, `numpy`, `openpyxl`), schema checks (`pandera`), modeling and preprocessing (`scikit-learn`), experiment tracking (`mlflow`), hyperparameter optimization and its MLflow callback (`optuna`, `optuna-integration[mlflow]`), and saving the fitted pipeline (`joblib`).
