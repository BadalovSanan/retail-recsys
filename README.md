# Retail Recommender System
 Implicit-feedback product recommender system on the RetailRocket e-commerce dataset

## Problem

## Dataset
Source: [Retailrocket recommender system dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset?select=category_tree.csv)

In order to download easly in code, you can use:
```text
import kagglehub

# Download latest version
path = kagglehub.dataset_download("retailrocket/ecommerce-dataset")

print("Path to dataset files:", path)
```

## Approach

## Results

## Project Structure
```text
├── data/
│   ├── raw/         # (Gitignored) events.csv, item_properties, category_tree
│   └── processed/   # (Gitignored) train/test interaction matrices
├── models/          # (Gitignored) Trained ALS/GRU4Rec model files
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_modeling_als.ipynb
│   ├── 04_modeling_gru4rec.ipynb
│   └── 05_evaluation_comparison.ipynb
├── results/
├── README.md
├── .gitignore
└── requirements.txt
```

## Setup instruction
1. Download dataset i referenced above
2. Unzip and add it to data/ folder
3. Open new terminal inside project (can be done with 'Ctrl' + 'Shift' + '`')
4. Write 'pip install -r requirements.txt'

## Progress Log
 
| Date | Commit |
|------|--------|
| 14 July | Initializing the Project |

## Link to other repositories i have
- [My Student Pass/Fail ML Project](https://github.com/BadalovSanan/My-StudentPassFail-ML-Project)
- [Casting Product's Deffect Detecting](https://github.com/BadalovSanan/casting-defect-logistic-regression)
- [Concrete Strength Linear Regression](https://github.com/BadalovSanan/concrete-strength-linear-regression)
- [Credit Card Customer Segmentation](https://github.com/BadalovSanan/credit-card-customer-segmentation)
- [Network Intrusion Detection with Random Forest & XGBoost](https://github.com/BadalovSanan/Network-Intrusion-Detection-with-Random-Forest-and-XGBoost)
- [Predictive Maintenance Anomaly Detection Project](https://github.com/BadalovSanan/Predictive-Maintenance-Anomaly-Detection)