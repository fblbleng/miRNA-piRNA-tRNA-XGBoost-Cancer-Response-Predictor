# miRNA-piRNA-tRNA-XGBoost-Cancer-Response-Predictor
# Predicting Cancer Treatment Response from Small RNA Profiles

This project implements a machine learning pipeline that integrates **miRNA**, **piRNA**, and **tRNA** datasets to predict the **treatment response** in cancer patients using **XGBoost**.

## 🧪 Pipeline Overview

1. **Data Integration**: Merge and normalize multi-RNA data.
2. **Feature Engineering**: Construct combined feature matrix.
3. **Modeling**: Train XGBoost classifier to predict response.
4. **Feature Selection**: Identify important biomarkers.
5. **Evaluation**: Performance metrics, ROC, confusion matrix.


## 🧬 Data Files
- `mirna.csv`, `pirna.csv`, `trna.csv`: Feature tables with patient IDs
- `metadata.csv`: Contains labels (e.g., `patient_id`, `response`)

## 🚀 Getting Started
```bash
git clone https://github.com/yourusername/rna-xgboost-response.git
cd rna-xgboost-response
pip install -r requirements.txt
```

