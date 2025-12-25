# Breast-Cancer-Prediction-Using-ML

Learning-focused project to explore, train, and evaluate machine learning models for breast cancer prediction.

## Folder structure
- `data/`: raw and cleaned datasets (place `breast_cancer.csv` here)
- `models/`: saved trained models and preprocessing artifacts
- `notebooks/`: exploratory data analysis and experiments
- `scripts/`: reusable training/inference utilities
- `results/`: evaluation outputs, plots, and reports

## Quickstart
1) Create a virtual environment (optional but recommended)
```
python -m venv .venv
.\.venv\Scripts\activate
```
2) Install dependencies
```
pip install -r requirements.txt
```
3) Place the dataset into `data/` (rename or symlink if needed).
4) Run experiments via notebooks or scripts.
   - Notebook: open `Advance Project Breast Cancer Prediction Using ML.ipynb` (or copy/move into `notebooks/`).
   - Script (example pattern): `python scripts/train.py --data data/breast_cancer.csv --out models/model.pkl`.
