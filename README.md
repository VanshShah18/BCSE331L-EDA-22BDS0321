# 📊 Exploratory Data Analysis – Penguins Dataset  
### BCSE331L – Data Analytics Laboratory  
### **Name:** Vansh Shah  
### **Reg. No:** 22BDS0321  

---

## ✅ Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Tools & Libraries Used](#tools--libraries-used)  
4. [Phase 1 – Data Loading & Cleaning](#phase-1--data-loading--cleaning)  
5. [Phase 2 – Exploratory Data Analysis](#phase-2--exploratory-data-analysis)  
6. [Phase 3 – Advanced Analysis](#phase-3--advanced-analysis)  
7. [Visualizations Included](#visualizations-included)  
8. [Conclusion](#conclusion)  
9. [How to Run](#how-to-run)  

---

# 📘 Project Overview
This repository contains the complete Exploratory Data Analysis (EDA) of the Palmer Penguins dataset for the BCSE331L Data Analytics Lab.  
The notebook includes:

- Data loading and cleaning  
- Full univariate, bivariate, and multivariate analysis  
- Advanced statistical computations  
- PCA dimensionality reduction  
- K-Means clustering  
- Regression modelling + evaluation  
- 30+ high-quality visualizations  

Every plot includes the registration number **22BDS0321** as required.

---

# 🐧 Dataset Description
The dataset includes features describing physical measurements of penguins.

| Feature | Description |
|---------|-------------|
| species | Adelie, Chinstrap, Gentoo |
| island | Biscoe, Dream, Torgersen |
| culmen_length_mm | Bill length |
| culmen_depth_mm | Bill depth |
| flipper_length_mm | Flipper length |
| body_mass_g | Body mass |
| sex | Male/Female |

Missing values were cleaned before analysis.

---

# 🔧 Tools & Libraries Used
- Python  
- Google Colab  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Plotly  
- Scikit-learn  
- Statsmodels  

---

# ✅ Phase 1 – Data Loading & Cleaning
- Loaded dataset from CSV  
- Performed `.info()`, `.describe()`  
- Converted categorical columns  
- Handled missing values  
- Cleaned dataset for analysis  

---

# ✅ Phase 2 – Exploratory Data Analysis

---

## 🟦 Univariate Analysis
### **Statistical Measures**
- Mean, Weighted Mean, RMS  
- Harmonic & Geometric Mean  
- Median, Mode  
- Quantiles, Deciles, Percentiles  
- Range, IQR, Interdecile Range  
- Variance, Standard deviation  
- Skewness, Kurtosis  
- Frequency and Relative Frequency  

### **Visualizations**
- Histogram  
- Density Plot  
- Box Plot  
- Violin Plot  
- Dot Plot  
- ECDF Plot  
- Pie Chart  
- Bar Chart  

---

## 🟩 Bivariate Analysis

### **Numeric vs Numeric**
- Scatter Plot  
- Regression Plot  
- LOWESS Smooth Plot  
- Joint Plot  
- Joint KDE Plot  
- Hexbin Plot  
- Correlation Matrix & Heatmap  
- Pairplot  
- Bubble Plot  

### **Categorical vs Numeric**
- Box Plot  
- Violin Plot  
- Swarm Plot  
- Strip Plot  
- Barplot of Means  
- Density by Category  
- Point Plot  
- Facet Grid  

### **Categorical vs Categorical**
- Contingency Table  
- Grouped Bar Chart  
- Stacked Bar Chart  
- Proportional Bar Chart  
- Heatmap of Counts  
- Mosaic Plot  

---

## 🟥 Multivariate Analysis (3D)
- Global 3D Scatter Plot  
- Species-wise Faceted 3D Scatter Plots  
- Bubble Plot (x, y, size, color)  
- Spider / Radar Charts  

---

# ✅ Phase 3 – Advanced Analysis

---

## 🔷 PCA (Principal Component Analysis)
- Standardization of features  
- Eigenvalues and explained variance  
- Scree Plot  
- Component Loadings  
- PC1 vs PC2 Scatter Plot  
- PCA Biplot  

**Variance Explained:**  
- PC1 ≈ 68.7%  
- PC2 ≈ 19.3%  
- Combined ≈ 88%  

---

## 🔶 K-Means Clustering
- Scaled features  
- Elbow Method (k = 1–10)  
- Optimal clusters = **3**  
- Fitted K-Means  
- Clustered 2D & 3D scatter plots  
- Cluster center analysis  

---

## 🔵 Regression Modelling
### ✅ Simple Linear Regression
- Predictor: Flipper Length  
- Response: Body Mass  
- Regression line  
- Metrics: MSE, RMSE, MAE, R²  

### ✅ Multiple Linear Regression
Predictors:  
- Culmen Length  
- Culmen Depth  
- Flipper Length  

Outputs:  
- Coefficients  
- P-values  
- Confidence intervals  
- VIF for multicollinearity  
- OLS full summary  

---

## 🟣 Evaluation Metrics
Included all major metrics:

| Metric | Included |
|--------|----------|
| MSE | ✅ |
| RMSE | ✅ |
| MAE | ✅ |
| R² | ✅ |
| Adjusted R² | ✅ |
| MAPE | ✅ |
| Explained Variance | ✅ |
| Residual Plots | ✅ |

---

# 🎨 Visualizations Included
✅ 30+ total visualizations including:  
- Radar charts  
- Faceted 3D scatter plots  
- PCA Biplot  
- Hexbin plot  
- ECDF plot  
- Clustered scatter  
- Pairplot  
- Density overlays  
- Full bivariate grid  

Every graph is titled with  
**Reg. No: 22BDS0321**

---

# ✅ Conclusion
This project performs a complete and thorough Exploratory Data Analysis of the Penguins dataset.  
It covers:

- Statistical analysis  
- Visualization-driven insights  
- Clustering  
- Dimensionality reduction  
- Regression modelling  
- Error & performance evaluation  

The notebook satisfies **all requirements** from Phase 1, Phase 2, and Phase 3.

---

# ▶️ How to Run
1. Open the notebook in **Google Colab**  
2. Upload `penguins_size.csv`  
3. Run all cells sequentially  
4. All visualizations will generate automatically  

---

