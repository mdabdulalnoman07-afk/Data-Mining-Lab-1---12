# Astronomy Data Analysis – Data Mining Lab 12

## Project overview
This repository contains a Jupyter Notebook project that explores an astronomy-inspired star dataset and uses machine learning to classify stars into four broad categories:

- Main Sequence
- Giant
- Supergiant
- White Dwarf

The workflow includes CSV loading, data inspection, missing-value handling, duplicate removal, exploratory data analysis (EDA), visualizations, correlation analysis, feature importance, preprocessing, model training, model comparison, and evaluation.

## Important dataset disclosure
`astronomy_stars.csv` is a **synthetically generated educational dataset**. It is not downloaded from a telescope archive and does not contain verified measurements of real stars. Its values are designed to be broadly astronomy-inspired so the data-mining workflow can be demonstrated reproducibly. Please describe it as synthetic if presenting the project.

## Files
| File | Description |
|---|---|
| `Astronomy_Data_Analysis_Lab12.ipynb` | Complete Jupyter Notebook for the project |
| `astronomy_stars.csv` | Dataset used by the notebook |
| `README.md` | Project documentation |
| `requirements.txt` | Python package dependencies |

## Dataset columns
| Column | Description |
|---|---|
| `Star_ID` | Unique educational record identifier |
| `Temperature_K` | Surface temperature in Kelvin |
| `Luminosity_Lsun` | Luminosity relative to the Sun |
| `Radius_Rsun` | Radius relative to the Sun |
| `Absolute_Magnitude` | Absolute magnitude |
| `Color_Index` | Simplified colour-index value |
| `Spectral_Class` | Simplified spectral class (O, B, A, F, G, K, M) |
| `Distance_LY` | Distance in light-years |
| `Apparent_Magnitude` | Apparent magnitude |
| `Star_Type` | Target class for classification |

## How to run
1. Download or clone this repository.
2. Install Python 3.9 or later.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `Astronomy_Data_Analysis_Lab12.ipynb`.
6. Run the notebook cells from top to bottom. Keep `astronomy_stars.csv` in the same folder as the notebook.

## Machine-learning models
The notebook compares:
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting

The best model is selected from the held-out test-set accuracy and assessed using a classification report and confusion matrix. Results are calculated when the notebook is run; the README does not promise a fixed accuracy.

## Tools and libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Limitations
Because the included dataset is synthetic, its model scores are only for demonstrating the workflow. They should not be interpreted as scientifically valid results about real stars. For research-grade analysis, replace the CSV with a documented public astronomy catalogue and review its measurement units, selection effects, and target-label definitions.

## Author
Name: Md. Abdul Al Noman
Student ID: 232031044
31st (UG)
CSE Department
