# Machine Learning Projects Portfolio

End-to-end machine learning solutions covering **multi-class classification**, **continuous regression**, and **unsupervised customer segmentation**, implemented in Google Colab and documented in an executive business report.

## Repository Contents

* **`Bushra_ML_Projects.ipynb`** — Complete Python/scikit-learn implementation for all three projects, including data inspection, preprocessing, required experiments, evaluation metrics, visualizations, and management review notes.
* **`Bushra_Almasalmeh_ML_Report.docx`** — Business-focused report summarizing objectives, datasets, preparation steps, model comparisons, final evaluations, visual evidence, recommendations, and limitations without raw code blocks.

## Projects Overview

| Project | Task Type | Selected Model | Key Validation / Selection Metric | Final Test / Segment Outcome |
| :--- | :--- | :--- | :--- | :--- |
| **1. Product Sample Classification** | Multi-Class Classification | Support Vector Machine (`C=1`, `kernel='rbf'`) with training-fitted `StandardScaler` | Validation Macro F1: `1.0000` | Test Accuracy: `97.22%` (`0.9722`), Test Macro F1: `0.9696` (35/36 test samples correct) |
| **2. Regional Housing Value Estimation** | Continuous Regression | Random Forest Regressor (`n_estimators=100`, `max_depth=None`, `random_state=42`) | Validation RMSE: `0.5163` (`$51,632`) | Test MAE: `$34,283.67` (`0.3428`), Test RMSE: `$52,346.20` (`0.5235`), Test R²: `0.8002` |
| **3. Wholesale Customer Segmentation** | Unsupervised Clustering | K-Means (`n_clusters=2`, `random_state=42`, `n_init=10`) on `log1p` + `StandardScaler` spending features | Silhouette Score: `0.2903` (Davies-Bouldin: `1.3515`) | 2 segments: `252` Foodservice buyers (`57.27%`) & `188` Retail stockists (`42.73%`) |

## Author

* **Bushra Emad Almasalmeh** — November 26, 2026
