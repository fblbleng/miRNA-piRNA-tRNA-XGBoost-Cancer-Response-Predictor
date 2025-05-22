# RNA Feature Integration & XGBoost Pipeline for Cancer Response Prediction

This repository contains an R-based pipeline that integrates miRNA, piRNA, and tRNA expression datasets to predict treatment response in cancer patients using XGBoost.

### 🔬 Workflow Overview

1. **Preprocessing**
   - Load and clean RNA datasets
   - Merge datasets on patient IDs
   - Normalize features (z-score)
   - Match samples with metadata to extract treatment response labels

2. **Modeling**
   - Use XGBoost with cross-validation
   - Feature importance analysis
   - Output top predictive RNA signatures

### 📁 Directory Structure

- `data/` - Input RNA and metadata CSVs
- `results/` - Preprocessed data and model outputs
- `scripts/` - R scripts and notebooks
- `README.md` - Project overview

### 🧬 Scripts

#### `scripts/01_preprocess_rna.Rmd`

This script:
- Loads miRNA, piRNA, and tRNA datasets
- Merges them by patient ID
- Normalizes expression values
- Extracts treatment response from metadata

#### `scripts/02_xgboost_model.R` (To be created)

This will:
- Load preprocessed data
- Train an XGBoost classifier
- Output feature importance and AUC metrics

### 📦 Dependencies

Install required R packages:

```r
install.packages(c("dplyr", "readr", "scales", "tibble", "xgboost", "caret", "Matrix"))
