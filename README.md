# house_kaggle
Kaggle project
Run conda env create -f environment.yml to install the dependencies before open the .ipynb file
The gridsearch experiments captured by mlflow are stored in the mlflow_tracking_titanic.sql file
To check the scores using mlflow, run mlflow server --backend-store-uri mysql://{db_user}:{password}@{db_host}/{database_name} --default-artifact-root ./mlruns --host 0.0.0.0 --port 5000
Best Score: 0.11818
link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview
