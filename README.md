# Palmer Penguins Classification

Machine learning project classifying penguin species using morphological features.

## Presentation

[View Slides](https://www.canva.com/design/DAG25qCd7No/AZ4Fp0NxeEKuEGSWMx_UQg/edit?utm_content=DAG25qCd7No&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Notebooks

1. **EDA.ipynb** - Exploratory data analysis
2. **CleanFE.ipynb** - Data cleaning and feature engineering
3. **TestLeakage.ipynb** - Data leakage verification
4. **PreprocessValidation.ipynb** - Preprocessing validation (5/95 stress test)
5. **TrainTune.ipynb** - Model training and tuning (70/30 split)
6. **EvalInterp.ipynb** - Model evaluation and interpretation (LIME & SHAP)

## Key Results

- **Best Model:** Logistic Regression
- **Accuracy:** 99.04%
- **F1-Score:** 0.9918

## Preprocessing

- MICE imputation for numerical features
- IterativeImputer for Sex feature
- StandardScaler normalization
- SMOTE oversampling (k_neighbors=5)

## Interpretation

- **LIME:** Local explanations for individual predictions
- **SHAP:** Feature importance and contribution analysis