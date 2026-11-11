<div align="center">

# 💳 CreditScope
### *Exploring credit data, finding patterns, and making predictions.*
</div>
**CreditScope** is our data science midterm project — a hands-on journey through a credit dataset, from raw exploration to honest model evaluation.

![Project Stage](https://img.shields.io/badge/stage-EDA%20%2B%20Feature%20Selection-7C5CFF?style=flat-square)
![Python](https://img.shields.io/badge/python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Rows](https://img.shields.io/badge/dataset-400%20rows%20%C2%B7%2011%20cols-2E8B57?style=flat-square)



---

## 🧭 About the Project

The idea is simple: **understand the data first, then build models.**

We explore how customer and financial features relate to each other, whether natural groups emerge in the data, and which features could help predict credit balance. No shortcuts, no black boxes — every step is documented and justified.

---

## 🗃️ The Dataset

We work with `Credit_Cleaned.csv`.

| Quick Facts | |
|---|---:|
| **Rows** | 400 |
| **Columns** | 11 |
| **Missing Values** | 0 |
| **Numeric Columns** | 10 |
| **Categorical Columns** | 1 (`region`) |

The dataset covers **income**, **credit limit**, **credit rating**, **number of cards**, **age**, **education**, **homeownership**, **student** and **marital status**, **region**, and **balance**.

---

## 🗺️ Roadmap

Our project follows the assignment in five stages:

- [x] **1. Prepare the data** — clean it and confirm it's ready to analyze ✅
- [x] **2. Explore the data** — descriptive stats, PairGrids, association metrics, PPS, PCA, UMAP & HDBSCAN clustering 🧪 ✅
- [ ] **3. Choose what to predict** — pick a continuous target and a useful feature set 🎯
- [ ] **4. Build models** — compare linear regression vs. random forest, with and without cluster info 🤖
- [ ] **5. Evaluate & explain** — R² scores, residual & correlation plots, and a look at Simpson's Paradox 🔍

> [!NOTE]
> **Current focus:** stages **2 & 3**. Modeling and evaluation begin once the target and feature set are locked in.

---

## 🛠️ Tech Stack

| Purpose | Tools |
|---|---|
| Data wrangling | `pandas` · `numpy` |
| Visualization | `matplotlib` · `seaborn` |
| Modeling | `scikit-learn` |
| Advanced exploration | `ppscore` · `umap-learn` · `hdbscan` |
| Environment | Jupyter Notebook |

---

## 🚀 Getting Started

**1. Clone the repo**

```bash
git clone https://github.com/jirosheno/DataScienceProject.git
cd <repository-folder>
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Launch Jupyter**

```bash
jupyter notebook
```

Place the cleaned CSV in the `data/` folder, then load it:

```python
import os # Optional
import pandas as pd

df = pd.read_csv("../Data/Credit_Cleaned.csv") # the location of the dataset
df.head()
```

---

## 📁 Repository Layout

```text
CreditScope/
├── data/
│   └── Credit_Cleaned.csv
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_feature_selection.ipynb
│   └── 04_modeling_and_evaluation.ipynb
├── outputs/
│   ├── figures/
│   └── results/
└── README.md
```

---

## 🤝 Working Together

> [!TIP]
> A few ground rules to keep things smooth:

- 🔄 Pull the latest changes before starting.
- ✋ Avoid editing the same notebook at the same time.
- 🗂️ Keep plots and results organized in `outputs/`.
- 📝 Add short notes explaining **important findings** — not just code and screenshots.
- ✅ Agree on the **target**, **selected features**, and **cluster labels** before modeling begins.

---

## 🏁 The Goal

By the end, we want three things:

1. 🧠 A **clear picture** of the dataset and its patterns.
2. 🎯 A **justified feature set** and prediction target.
3. ⚖️ An **honest model comparison** — if clusters help prediction, we'll show it. If they don't, that's a result too.

---

<div align="center">

*CreditScope · Data Science Midterm Project 💳*

</div>

