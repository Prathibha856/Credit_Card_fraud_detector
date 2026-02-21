# Credit Card Fraud Detector

This repository contains a hands-on credit card fraud detection project implemented in a Jupyter notebook. The notebook demonstrates data loading, preprocessing, model training, evaluation, and baseline results.

## Contents
- `credit_card_fraud.ipynb` — notebook with EDA, preprocessing, model training and evaluation.
- `creditcard.csv` — dataset (anonymized features V1..V28, `Time`, `Amount`, `Class`). NOTE: the CSV is large and has been excluded from the remote repository to meet GitHub size limits. See "Dataset" below.

## Quick start

1. Clone the repository:

```bash
git clone https://github.com/Prathibha856/Credit_Card_fraud_detector.git
cd Credit_Card_fraud_detector
```

2. (Optional) Create a virtual environment and install packages:

```bash
python -m venv .venv
# Windows PowerShell:
. .venv\Scripts\Activate.ps1
# macOS / Linux:
source .venv/bin/activate

pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter
```

3. Open the notebook:

```bash
jupyter notebook credit_card_fraud.ipynb
```

## Dataset

The `creditcard.csv` used for development is large (>100MB) and was not pushed to GitHub. To run the notebook locally:

- Place your local `creditcard.csv` file in the repository root.
- Or host the CSV on cloud storage and download it before running the notebook.

If you prefer the dataset inside the repo, use Git LFS or an external host (S3/GDrive) and update this README with a download link.

## What the notebook includes

- Data loading and inspection
- Exploratory data analysis and visualization
- Handling class imbalance (resampling and class weights)
- Feature scaling and preprocessing
- Baseline model training and evaluation (metrics: precision, recall, F1, ROC-AUC)

## Roadmap

- Add algorithm comparisons (Random Forest, XGBoost, LightGBM, Neural Networks).
- Add model persistence and a small inference script.
- Add automated training/evaluation scripts and summary plots in the README.

## Contributing

Contributions welcome. For large files use Git LFS or external hosting and open a PR updating this README with dataset links.

Repository owner: Prathibha856
