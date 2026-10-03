# Ductile vs Brittle Material Classifier

**Machine Learning Project**

This project predicts whether a material is **Ductile** or **Brittle** based on its physical and mechanical properties using Machine Learning techniques.

---

## Project Overview

Using a dataset of **13,000+ materials**, this system classifies material behavior (Ductile / Brittle) by analyzing key properties such as:

- Bulk Modulus, Shear Modulus, Young’s Modulus
- Pugh Ratio, Poisson Ratio
- Debye Temperature, Density
- Sound Velocities & Thermal Conductivity

The project includes **Feature Engineering**, **Model Training**, **SHAP Analysis**, and an interactive **Material Behavior Predictor**.

---

## Key Features

- Binary Classification (Ductile vs Brittle)
- Feature Engineering:
  - Stiffness Ratio
  - Brittleness Index
  - Elastic Ratio
- Multiple Machine Learning models comparison
- SHAP Analysis for feature importance (Explainable AI)
- Interactive Material Behavior Predictor
- Well-documented Google Colab notebook

---

## Dataset

| Detail              | Information                  |
|---------------------|------------------------------|
| File                | `materials_13073.csv`        |
| Total Materials     | 13,073                       |
| Target Variable     | Behavior (Ductile / Brittle) |
| Features            | 16+ material properties      |

---

## How to Run

### Option 1: Google Colab (Recommended)
1. Open the notebook `IMI_ML_PROJECT.ipynb` in Google Colab.
2. Upload the dataset `materials_13073.csv`.
3. Run all cells in order.
4. Use the final cell to predict the behavior of any new material.

### Option 2: Local Jupyter Notebook
```bash
pip install pandas numpy scikit-learn shap matplotlib seaborn
jupyter notebook IMI_ML_PROJECT.ipynb
