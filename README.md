
# Churn – Decision Tree (Explainable Classifier)

This repository contains my Jupyter notebook for **customer churn prediction** using a **Decision Tree**.  
The focus is interpretability: besides standard metrics, the model’s **rules** can be exported and inspected.

---

## Files
- `notebooks/CleanedData_with_DecisionTree.ipynb` — main notebook (EDA → preprocessing → model → evaluation).
- (Optional) other notebooks (Logistic Regression, Neural Network) may be included for comparison.


## Dataset
- Place your dataset at **`data/raw/churn.csv`** (or adjust the path in the notebook).
- Target column (suggested): **`churn`** with values **0/1**.  
  If your labels are `"Yes"/"No"`, adapt the mapping inside the notebook.

---

## How to open and run

### A) Using Jupyter Notebook (recommended)
1. **Create a virtual environment**
   ```bash
   python -m venv .venv
   # Windows
   source .venv/Scripts/activate
   # macOS/Linux
   # source .venv/bin/activate
