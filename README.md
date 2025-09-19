# Data Science Bootcamp – Days 11–20

This repository contains the second stage of my **self-guided Data Science Bootcamp**, continuing from [Days 1–10]((https://github.com/hansolothe3rd/Refresh.git)).  
The focus here is building on the foundations with deeper dives into **data analysis, visualization, and real-world mini projects**.

---

## 📅 Daily Progress

### Day 11
- New repo setup for Days 11–20
- Reviewed Python and pandas basics
- Practiced with Iris dataset (exploration + visualization)
- Planned roadmap for upcoming days

### Day 12
- Practiced data cleaning with Titanic dataset
- Handled missing values (drop vs fill strategies)
- Detected and reviewed outliers
- Cleaned categorical columns (embarked, sex)
- Saved cleaned dataset for future use


### Day 13
- Created new features (family size, age group bins)
- Encoded categorical features (manual + automated with OneHotEncoder)
- Used `SimpleImputer` for missing value handling
- Scaled numeric features with `StandardScaler`


### Day 14
- Practiced advanced visualizations with Titanic dataset
- KDE plots for smooth distributions
- Correlation heatmaps for numeric variables
- Scatterplots with regression lines
- Subplots for side-by-side comparisons


### Day 15 – Mini Project 2: Wine Quality EDA
- Loaded new Wine Quality dataset (red wine)
- Cleaned missing values and duplicates
- Explored descriptive statistics
- Visualized key relationships (histograms, boxplots, scatterplots, heatmaps)
- Summarized insights on features affecting wine quality


### Day 16 – Intro to Statistics
- Reviewed descriptive statistics (mean, median, std)
- Explored probability distributions (normal and uniform)
- Demonstrated Central Limit Theorem with sampling
- Visualized distributions with histograms and KDE plots


### Day 17 — Hypothesis Testing
- Learned hypothesis testing framework (H₀, H₁, errors, alpha).
- Performed:
  - One-sample t-test
  - Two-sample t-test
  - Chi-Square test
- Applied tests with `scipy.stats` on real and categorical data.
- Prepared for ANOVA & Regression (Day 18).


### Day 18
- Explored linear relationships with scatter plots.
- Fitted a simple linear regression model (`alcohol ~ density`).
- Visualized regression line and predictions.
- Evaluated model performance with MAE, MSE, RMSE, and R².
- Prepared for multiple regression (Day 19).


## Day 19 – Correlation & Covariance

**Concepts Covered:**
- Covariance vs correlation.
- Using correlation matrices for feature selection.
- Interpreting positive/negative correlations.

**Practice:**
- Computed correlation matrix of the `wine_clean.csv` dataset.
- Identified top features correlated with wine quality.
- Visualized results with a heatmap.

**Mini Project: Wine Quality Correlation Study**
- Explored which features most influence wine quality.
- Found that `alcohol` positively correlates with quality, while `volatile_acidity` negatively correlates.
- Built a foundation for selecting features in future regression models.


## Day 20 – Feature Scaling & Mini Project

**Concepts Covered:**
- Why scaling features is necessary in ML.
- Normalization vs. Standardization.
- Impact of scaling on model performance.

**Practice:**
- Applied MinMaxScaler and StandardScaler to the wine dataset.
- Created new scaled datasets for modeling.

**Mini Project: k-NN Wine Quality Prediction**
- Trained k-NN classifier on raw vs. standardized data.
- Found that scaling significantly improved accuracy.
- Demonstrated importance of preprocessing before ML.


---

## 🔗 Related Repos
- [Days 1–10 Bootcamp][(https://github.com/hansolothe3rd/Refresh.git)]

---

## ⚖️ License
This project is licensed under the **MIT License** – feel free to use, modify, and share.

---

## ✍️ Notes
This repo will evolve daily as I progress through the bootcamp.  
Stay tuned for mini projects, visualizations, and deeper dives into machine learning.


