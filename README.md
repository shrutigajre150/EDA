# EDA

# Heart Disease Risk Analysis

## Project Overview
This repository showcases an end-to-end exploratory data analysis (EDA) and visualization workflow applied to the UCI Cleveland Heart Disease dataset. Using Python’s data ecosystem—pandas, NumPy, matplotlib and seaborn—you’ll find a structured investigation into 303 patient records across 14 clinical attributes, aimed at uncovering patterns, correlations and actionable insights related to cardiovascular risk.

## 📂 Dataset
Source: heart.csv (UCI Cleveland Heart Disease)

Shape: 303 rows × 14 columns

## Features:

Continuous: age (years), trestbps (resting BP in mm Hg), chol (serum cholesterol mg/dl), thalach (max heart rate bpm), oldpeak (ST depression)

Categorical/Binary: sex, cp (chest pain type), fbs (fasting blood sugar), restecg, exang (exercise‐induced angina), slope, ca, thal

Target: presence of heart disease (0 = no, 1 = yes)

## 🛠 Methodology
Data Loading & Validation

Loaded the CSV into a pandas DataFrame; confirmed dimensions (303×14) and zero missing values.

### Descriptive Statistics

Computed summary stats:

Mean age = 54.37 ± 9.08 years

Mean resting BP = 131.62 ± 17.54 mm Hg

Mean cholesterol = 246.26 ± 51.83 mg/dl

Mean max heart rate = 149.65 ± 22.91 bpm

Mean ST depression = 1.04 ± 1.16 units

#### Univariate Analysis

Histograms & boxplots for continuous variables; countplots for categorical features.

#### Bivariate & Multivariate Analysis

Generated a Pearson correlation matrix and heatmap, highlighting key relationships (see “Key Insights”).

Employed seaborn pairplots to visualize scatter‐based interdependencies among numeric variables.

## Key Insights

Chest pain type exhibits the strongest positive correlation with heart disease (r = 0.43).

Exercise‐induced angina shows a strong negative correlation (r = –0.44).

Patients with heart disease have a 19.37 bpm higher mean max heart rate (158.47 vs 139.10 bpm) and a 1.01-unit lower mean ST depression (0.58 vs 1.59) compared to those without.

## ⚙️ Tools & Technologies
Languages: Python 3.x

Libraries: pandas, NumPy, matplotlib, seaborn

Environment: Jupyter Notebook

