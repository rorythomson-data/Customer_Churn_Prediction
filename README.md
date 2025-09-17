# Customer Churn Prediction (Capstone)

Fintech customer churn prediction with Python (scikit-learn, CatBoost/XGBoost).  
See `notebooks/` for the workflow and `reports/papers/` for the written report.

## Quickstart
Run:
- `python -m pip install -r requirements.txt`
- `jupyter notebook`

## Repository structure
- `notebooks/` — EDA, feature engineering, modeling
- `data/` — local data (ignored). Keep tiny samples in `data/sample/`
- `models/` — trained models/artifacts (ignored)
- `artifacts/` — run logs (e.g., CatBoost) (ignored)
- `reports/` — figures and papers (PDF)

## Reproducibility
- Heavy data/models are not tracked; re-run notebooks with your local data.
- CatBoost logs go to `artifacts/` to keep the repo clean.

## Suggested visuals (commit PNGs under `assets/` and reference here)
- ROC & PR curves
- Confusion matrix @ chosen threshold
- Feature importance (CatBoost/XGBoost)

---

## Español

**Predicción de churn** en un contexto fintech con Python (scikit-learn, CatBoost/XGBoost).  
Consulta `notebooks/` para el flujo de trabajo y `reports/papers/` para la memoria.

**Cómo empezar**
Ejecuta:
- `python -m pip install -r requirements.txt`
- `jupyter notebook`

**Notas**
- Datos y modelos pesados se mantienen fuera del repo.
- Logs a `artifacts/`. Figuras a `assets/` o `reports/`.
