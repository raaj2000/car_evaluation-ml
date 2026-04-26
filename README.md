# Car Evaluation ML Project

This project predicts car acceptability classes using machine learning models.

## Project Goal
- Load and explore the car evaluation dataset.
- Train multiple models.
- Compare model performance using accuracy, balanced accuracy, and F1-macro.
- Visualize class distribution, confusion matrix, and feature importance.

## Dataset
- File used: `car.csv`
- Features:
  - buying
  - maint
  - doors
  - persons
  - lug_boot
  - safety
- Target:
  - class

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Main Files
- `car_ml_project_Final.ipynb` : Final notebook version

- `car.csv` : Dataset

## How To Run
1. Open the project folder in VS Code or Jupyter.
2. Install required libraries:

```bash
pip install pandas matplotlib seaborn scipy scikit-learn
```

3. Run `car_ml_project_Final.ipynb` cell by cell.
4. Check printed metrics and generated plots.

## Evaluation Included
- Train/test split with stratification
- Classification report
- Confusion matrix
- Per-class recall and F1 comparison
- 5-fold cross-validation
- Random Forest feature importance

## Notes
- Logistic Regression is configured with balanced class weights.
- Random state is used in splitting and tree-based models for reproducibility.

## Author
- Raja shekhar Dasari as a ML Project




