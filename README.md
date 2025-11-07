# 📊 BCSE331L – Exploratory Data Analysis  
### **Reg. No: 22BDS0321**  
### **Student: Vansh Shah**  
### **Dataset: Penguins Size Dataset (palmerpenguins)**

This repository contains my Exploratory Data Analysis project completed for BCSE331L.  
All work has been completed in **Google Colab** and saved to GitHub as `22BDS0321.ipynb`.

The project is divided into **three phases**, based on the evaluation instructions provided.

---

# ✅ Phase 1 – Data Loading & Basic Exploration

### ✔ Google Colab → GitHub Integration
- Notebook saved through **“Save a copy in GitHub”**  
- Code written & executed in Colab  
- Dataset loaded directly from URL

### ✔ Basic Dataset Checks
- Shape (rows × columns)  
- Column-wise data types  
- Missing values  
- Summary statistics  
- Conversion of appropriate columns to `category`  
- Removal of incomplete rows only where required  
- Initial display of dataset

---

# ✅ Phase 2 – Complete Exploratory Data Analysis (EDA)

## ✅ 1D (Univariate Analysis)
Performed on both numeric and categorical variables:

- Mean, Median, Mode  
- Quantiles, Percentiles, Deciles  
- Range, IQR, Interdecile Range  
- Variance, Standard Deviation  
- Skewness, Kurtosis  
- Histogram  
- Density plot  
- ECDF (Cumulative distribution)  
- Box plot  
- Violin plot  
- Pie charts  
- Dot plot  
- Frequency & Relative Frequency Tables  

---

## ✅ 2D (Bivariate Analysis)

### **Numeric vs Numeric**
- Scatter plot  
- Regression line  
- Correlation heatmap  

### **Numeric vs Categorical**
- Boxplots  
- Violin plots  
- Grouped barplots (with error bars)  
- Density plots (by category)  
- Subgroup comparisons (species × sex)

### **Categorical vs Categorical**
- Crosstab  
- Heatmap  
- Countplots  
- Mosaic plot  

---

## ✅ 3D & Multivariate Analysis
- Pairplot (scatterplot matrix)  
- Bubble plot  
- Faceted scatter plots  
- 3D scatter plot  
- Radar / Spider charts  

---

## ✅ Clustering (K-Means)
- Scaling numeric variables  
- Elbow method (WCSS vs k)  
- KMeans model training  
- Cluster assignments visualized in 2D & 3D  
- Silhouette score  
- Cluster vs species comparison (crosstab)  
- Radar chart for cluster means  
- Heatmap of cluster centers  

---

# ✅ Phase 3 – Advanced Analysis (PCA + Regression + Evaluation)

> *All later analysis (Regression + Metrics + Classification bonus) is included under Phase-3 as per updated instructions.*

---

## ✅ A. PCA (Principal Component Analysis)
- Standardized numerical columns  
- Extracted Eigenvalues  
- Extracted PCA loadings  
- Scree plot  
- Selected optimal number of components  
- PCA scatter plot (PC1 vs PC2)  
- PCA biplot with variable loadings  
- Interpretation summary  

---

## ✅ B. Linear Regression

### **Simple Linear Regression**
- Predictor: `flipper_length_mm`  
- Target: `body_mass_g`  
- Regression line plotted  
- Intercept & slope  
- MSE, RMSE, MAE  
- R² (auto + manual)

### **Multiple Linear Regression**
Predictors:  
- `flipper_length_mm`  
- `culmen_length_mm`  
- `culmen_depth_mm`

Performed using `statsmodels.OLS` for full statistical summary.

### **Multicollinearity Check**
- Variance Inflation Factor (VIF)

### **Residual Analysis**
- Residual plot  
- Residual distribution (normality check)  

---

## ✅ C. Model Evaluation (Full Set of Metrics)
For multiple regression, calculated:

- MSE  
- RMSE  
- MAE  
- R²  
- Adjusted R²  
- Explained Variance Score  
- MAPE  
- Residual Summary  
- Diagnostic Plots  

---

# ✅ Final Notebook  
📄 **22BDS0321.ipynb**  
Contains:

- All three phases  
- Explanatory comments in each cell  
- Each visualization labeled with **22BDS0321**  
- Clear markdown write-ups  
- All evaluation metrics  
- PCA + Regression + Classification  

---

# ✅ Technologies Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Statsmodels  

---


