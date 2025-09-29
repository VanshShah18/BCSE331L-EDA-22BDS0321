# BCSE331L – Exploratory Data Analysis Project

**Name:** Vansh Shah  
**Roll No:** 22BDS0321  

---

## 📌 Project Overview
This repository contains my Exploratory Data Analysis (EDA) work for the **BCSE331L course project**.  
The analysis is performed on the **Palmer Penguins Dataset**, which provides measurements of different penguin species.

---

## 📂 Dataset Details
- **Source:** [penguins_size.csv](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/penguins_size.csv)  
- **Attributes:**
  - `species` – Penguin species  
  - `island` – Island where data was collected  
  - `sex` – Gender of the penguin  
  - `culmen_length_mm` – Bill length in mm  
  - `culmen_depth_mm` – Bill depth in mm  
  - `flipper_length_mm` – Flipper length in mm  
  - `body_mass_g` – Body mass in grams  

---

## 📊 Analysis Performed
1. **Dimensions & Summary Statistics**  
   - Dataset shape, info, and descriptive stats  

2. **Data Handling & Cleaning**  
   - Missing values  
   - Data type conversions  

3. **Univariate Analysis**  
   - Central Tendency: Mean, Median, Mode, Weighted Mean, RMS, Harmonic Mean, Geometric Mean  
   - Position & Dispersion: Quartiles, Deciles, Percentiles, Range, IQR, Variance, Std. Dev.  
   - Shape: Skewness, Kurtosis  
   - Frequency tables & Relative frequencies  
   - Visualizations: Histogram, Density plot, Frequency polygon, Dot plot, Bar chart, Pie chart, Box plot, Violin plot, Binned plots  

4. **Bivariate Analysis**  
   - Numeric vs Numeric: Scatter plots, Regression line, Correlation heatmap  
   - Categorical vs Numeric: Boxplots, Violin plots, Bar chart of means, Density plots  
   - Categorical vs Categorical: Contingency tables, Heatmap of counts, Stacked & Grouped bar charts  

5. **Multivariate Analysis**  
   - Pairplot (scatterplot matrix)  
   - Colored & shaped scatter plots  
   - Bubble plot (x, y, size, color)  
   - Faceting (scatter plots split by species)  
   - Multivariate correlation heatmap  

6. **Cluster Analysis (K-Means)**  
   - Scaling numeric variables (`culmen_length_mm`, `culmen_depth_mm`, `flipper_length_mm`, `body_mass_g`)  
   - Elbow method to identify optimal k  
   - K-Means clustering with `k=3`  
   - Cluster visualization (base scatter and seaborn scatter plots)  

---

## 🛠️ Tools & Libraries
- Google Colab  
- Python (3.x)  
- Pandas, NumPy, SciPy  
- Matplotlib, Seaborn  
- scikit-learn (for clustering)  

---

## 📅 Submission Phases
- **Phase I:** Till Multivariate Analysis (15 Aug 2025)  
- **Phase II:** Till Module 5 (02 Oct 2025)  
- **Phase III:** Full project with clustering + report (10 Nov 2025)  

---

## 📎 Notes
- The notebook file is saved directly from **Google Colab** into this GitHub repository.  
- All outputs and visualizations include my **Reg. No (22BDS0321)** in titles for identification.  
- Clustering was performed using **K-Means** with reproducible random seed.
