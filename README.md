# BCC Data Science Mini Bootcamp 2024: Wine Dataset Workshop

> A hands-on notebook from the post-workshop assignment (Day II) of the **BCC Data Science Mini Bootcamp 2024**. It walks through EDA, data preprocessing and a first classification model on the scikit-learn Wine dataset.

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/athaaaya/DSMBC_Athaya/blob/main/Pasca_Workshop_Athaya_Akbar_Andryansyah_245150401111034.ipynb)

---

## Overview

The notebook practises the core steps of a data science workflow on the [Wine dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#wine-recognition-dataset): 178 wines, 13 chemical measurements (alcohol, magnesium, flavanoids, proline and more) and 3 wine classes. The dataset is built into scikit-learn, so nothing needs to be downloaded.

## What's Covered

| Stage | Techniques |
|---|---|
| **EDA** | Mean, median and mode; range and quantiles (IQR); unique values; `loc` / `iloc` indexing; filtering with logical expressions |
| **Visualization** | Count plot, KDE density plot, correlation heatmap, box plot (Matplotlib and Seaborn) |
| **Preprocessing** | Missing-value checks, dropping and mean imputation (`SimpleImputer`); duplicate removal; IQR outlier detection and capping |
| **Encoding** | One-hot encoding (`pd.get_dummies`) and label encoding (`LabelEncoder`) |
| **Scaling** | Min-max scaling (`MinMaxScaler`) |
| **Modelling** | K-Nearest Neighbors classifier with a decision-boundary plot |
| **Evaluation** | Train/test split and accuracy score |

## Getting Started

### Option 1: Google Colab

Click the **Open in Colab** badge above and run all cells.

### Option 2: Local

```bash
git clone https://github.com/athaaaya/DSMBC_Athaya.git
cd DSMBC_Athaya
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

Then open `Pasca_Workshop_Athaya_Akbar_Andryansyah_245150401111034.ipynb`.

## Repository Structure

```
DSMBC_Athaya/
├── Pasca_Workshop_Athaya_Akbar_Andryansyah_245150401111034.ipynb
└── README.md
```

## Author

**Athaya Akbar Andryansyah**: [GitHub @athaaaya](https://github.com/athaaaya)
