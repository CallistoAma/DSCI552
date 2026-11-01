# Homework 5 — DSCI 552

Decision trees as interpretable models (Acute Inflammations) and LASSO / ridge / PCR / L1-penalized boosting for regression (Communities and Crime).

## Structure

```
HW5/
├── data/                 # raw UCI data files read by the notebook
│   ├── diagnosis.data
│   ├── diagnosis.names
│   ├── communities.data
│   └── communities.names
├── notebook/
│   ├── HW5.ipynb         # solution, executed with all outputs
│   └── HW5.pdf           # PDF export of the executed notebook
├── requirements.txt
├── .gitignore
└── README.md
```

## Running

```bash
pip install -r requirements.txt
cd notebook
jupyter notebook HW5.ipynb
```

The notebook reads data from `../data/`, so run it from inside `notebook/`. A full run takes about 4 minutes, mostly for the XGBoost cross-validation.
