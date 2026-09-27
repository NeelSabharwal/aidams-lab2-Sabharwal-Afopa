# aidams-lab2-Sabharwal-Afopa

This repository contains our completed Lab 2 notebook using the GIST Steel plant-level dataset.

## How to Run

The notebook was developed and tested using **Python 3.13**. Python 3.13 should be used to avoid compatibility issues with the required libraries.

### 1. Dataset

Make sure the GIST Steel dataset is located in the following path relative to the notebook:

`GIST Steel Dataset/Plant-level_data_Global_Iron_and_Steel_Tracker_June_2026_V1.xlsx`

### 2. Open the Notebook

Open `lab_2.ipynb` in VS Code or Jupyter and select a **Python 3.13** kernel.

### 3. Install Required Libraries

The first code cell installs the libraries required for the notebook:

```python
%pip install -q pandas numpy openpyxl pandera scikit-learn matplotlib mlflow optuna optuna-integration[mlflow]
```

Run this cell before running the rest of the notebook.

### 4. Restart the Kernel

After the libraries have finished installing, **restart the Jupyter kernel**.

After restarting, make sure **Python 3.13** is still selected as the kernel.

This step is important because some newly installed libraries may not be correctly available until the kernel has been restarted.

### 5. Run the Notebook

Run all cells from top to bottom.

The notebook covers the full modelling workflow, including:

- Data loading and inspection
- Schema validation with Pandera
- Data cleaning
- Feature engineering
- Exploratory analysis
- Baseline and linear regression models
- Cross-validation and model comparison
- Random Forest hyperparameter optimization
- Experiment tracking with MLflow
- Optuna optimization
- Model storage
- Deployment and model drift planning

The final trained pipeline is saved as:

`best_steel_production_pipeline.joblib`

The saved pipeline includes both the preprocessing steps and the trained model so that the same transformations are applied when the model is loaded again.
