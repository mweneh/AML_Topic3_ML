# Topic 3: Introduction to Machine Learning Using Python

This standalone student repository contains a practical notebook using mobile-money transaction data.

## Contents

- `notebook/topic3_introduction_to_machine_learning.ipynb` — guided Topic 3 practical
- `Data/mobile_money_statements.csv` — synthetic mobile-money dataset
- `requirements.txt` — Python packages used by the notebook

## Topics covered

- NumPy, Pandas, Matplotlib and Scikit-learn
- Loading and exploring data
- Features and target variables
- Missing-value imputation
- Categorical encoding
- Feature engineering and scaling
- Training/testing split
- Logistic Regression classification for `is_fraud`
- Linear Regression for derived `monthly_inflow_kes`
- Predictions, interpretation and evaluation

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook/topic3_introduction_to_machine_learning.ipynb
```

On Windows PowerShell, activate the environment with:

```powershell
.venv\Scripts\Activate.ps1
```

The dataset is synthetic and intended for teaching. Do not add post-outcome fields such as
`manual_review_score` or `settlement_status` to predictive features.
