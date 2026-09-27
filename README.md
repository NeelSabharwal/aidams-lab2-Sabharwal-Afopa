# aidams-lab2-Sabharwal-Afopa

This repository contains the completed Lab 2 notebook using the GIST Steel plant-level dataset.

## How to Run

The notebook was developed and tested using **Python 3.13**. Python 3.13 should be used to avoid compatibility issues with the required libraries.

### 1. Dataset Setup

The dataset is not included in this repository.

Download the following GIST Steel dataset file:

`Plant-level_data_Global_Iron_and_Steel_Tracker_June_2026_V1.xlsx`

Place the downloaded Excel file in the **same folder as `lab_2.ipynb`**.

The folder should therefore look like:

```text
project/
├── lab_2.ipynb
├── README.md
└── Plant-level_data_Global_Iron_and_Steel_Tracker_June_2026_V1.xlsx
```

No changes to the file path in the notebook should be required as long as the dataset keeps this filename and is placed in the same folder as the notebook.

### 2. Python Environment

Open `lab_2.ipynb` in VS Code or Jupyter and select **Python 3.13** as the notebook kernel.

### 3. Install Required Libraries

Run the first code cell in the notebook. This installs the required Python libraries.

After the installation finishes, **restart the Jupyter kernel**.

Make sure **Python 3.13** is still selected after restarting the kernel.

### 4. Run the Notebook

After restarting the kernel, run all cells from top to bottom.

The notebook covers the full modelling workflow, including:

- Data loading and validation
- Data cleaning
- Feature engineering
- Exploratory analysis
- Baseline modelling
- Linear Regression
- K-Fold Cross-Validation
- Ridge Regression and Random Forest comparison
- Hyperparameter tuning
- MLflow experiment tracking
- Optuna optimization
- Model storage
- Deployment and model drift planning

The notebook will also generate files used for experiment tracking and model storage during execution, including the final trained pipeline:

`best_steel_production_pipeline.joblib`

These generated files do not need to be downloaded separately before running the notebook.
