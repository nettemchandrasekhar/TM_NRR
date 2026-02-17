# NRR_TM

This repository contains machine learning workflows for **Nitrogen Reduction Reaction (NRR)** using transition metal descriptors. The notebooks cover **linear regression** and **tree-based models**, along with all associated data.

---

## Repository Structure

NRR_TM/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│ ├── Excel_sheet_all.xlsx
│ └── Excel_sheet.xlsx
│
├── LR/ # Linear Regression notebooks
│ ├── Linear_regression_F03_and_F01.ipynb
│ ├── Linear_regression_F03_F05.ipynb
│ ├── Linear_regression_F03_only.ipynb
│ ├── Linear_regression_F05.ipynb
│ ├── Linear_regression_F05_F06.ipynb
│ ├── Linear_regression_F08.ipynb
│ ├── Linear_regression_F08_F03.ipynb
│ └── Linear_regression_F09.ipynb
│
└── tree/ # Tree-based and other ML models
├── elasticnet.ipynb
├── gradient_boost.ipynb
├── KNN.ipynb
├── Lasso.ipynb
├── Randomforest.ipynb
├── Ridge.ipynb
├── SVR.ipynb
└── xgboost.ipynb


---

## Description

- **LR folder:** Notebooks implementing various linear regression models for NRR descriptors. Includes feature selection, scaling, training, testing, and Leave-One-Out cross-validation.  
- **tree folder:** Notebooks implementing tree-based and other regression models including ElasticNet, Gradient Boosting, Random Forest, XGBoost, KNN, SVR, Ridge, and Lasso.  
- **data folder:** Contains Excel sheets with all the NRR descriptors and target values used in the models.  

---

## Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
