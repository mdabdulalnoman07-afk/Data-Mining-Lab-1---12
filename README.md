# Data Mining Lab 1–12 — Jupyter Notebook Pack

## Contents
12 separate Jupyter notebooks covering the supplied Data Mining Lab Manual:
1. Python basics and CSV
2. Preprocessing and exploration
3. Visualization and EDA
4. Apriori
5. FP-Growth
6. Decision Trees
7. Naive Bayes
8. SVM
9. K-Means
10. Hierarchical clustering and DBSCAN
11. Outlier detection and Random Forest
12. End-to-end mini project

## Setup (Windows)
1. Install Python 3.10 or newer.
2. Open Command Prompt in this folder.
3. Run: `python -m pip install -r requirements.txt`
4. Run: `jupyter notebook`
5. Open a notebook and use **Kernel → Restart & Run All**.

## Dataset
The Adult Income notebooks first look for `adult.csv` in the current folder, then attempt to download the UCI Adult dataset. If unavailable, they create a clearly labelled synthetic teaching dataset so that the notebook can still run. Synthetic fallback results must not be presented as real-world dataset findings.

For Lab 4 and Lab 5, a small, explicitly illustrative transaction dataset is created inside the notebook.

## Important notes
- Run cells from top to bottom.
- The first run may require internet access to download the UCI dataset and install packages.
- If `adult.csv` is provided, it should contain the standard Adult dataset columns used in the notebook.
- Outputs are intentionally blank until you run the notebooks on your machine. Record your actual outputs and observations in your lab report.
- Lab 7's `OneHotEncoder(sparse_output=False)` requires a recent scikit-learn release; the requirements file pins a compatible version.
