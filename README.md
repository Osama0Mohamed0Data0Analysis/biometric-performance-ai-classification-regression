<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:1D4350,100:A43931&height=150&section=header&text=Biometric%20Performance%20AI&fontSize=34&fontColor=ffffff" alt="Biometric Performance AI project banner" width="100%" />

  <h1>Biometric & Physical Performance Prediction</h1>
  <p><strong>Classification and regression with machine learning</strong></p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
</div>

> An end-to-end machine-learning study using 13,392 records and 12 features to explore physical-performance outcomes.

## Project Overview

This project investigates two prediction tasks:

- **Classification:** predict performance grades (A/B/C/D).
- **Regression:** estimate broad-jump distance from physical measurements.

The workflow covers data exploration, outlier analysis, model training, and evaluation.

## Methods & Tools

- Python, Pandas, NumPy, Seaborn
- Scikit-learn models: KNN, Decision Tree, SVM, and Linear Regression
- MLP classifier and regressor neural networks
- IQR-based outlier analysis, correlation analysis, and model evaluation

## Results

| Task | Result |
|---|---|
| Classification — MLP `[128, 64]` | Test accuracy **74.65%**, F1 **0.7473** |
| Classification — 10-fold CV | Accuracy **0.7331 ± 0.013** |
| Regression — MLP `[128, 64]` / SVR | R² **0.7887**, RMSE **18.39 cm** |

## Visualizations

### Distributions and outliers
![Data distributions and outliers](assets/distribution_outliers.png)

### Correlation heatmap
![Correlation heatmap](assets/correlation_heatmap.png)

### Model comparison and confusion matrix
![Model comparison and confusion matrix](assets/model_comparison_confusion.png)

## Author

**Osama Mohamed** · [GitHub Profile](https://github.com/Osama0Mohamed0Data0Analysis)
