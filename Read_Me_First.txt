# 🇨🇦 Labour Force Segmentation Analysis – Canada (2014–2024)

###  Machine Learning + Power BI Project | By Guru Prasad Srinivasan

This project analyzes the Canadian Labour Force Survey (LFS) data from 2014–2024 to uncover workforce segments using KMeans clustering and visualizes employment trends using Power BI. It combines Python-based machine learning with professional BI storytelling, offering policy-level insights into underemployment, wage disparity, and regional labour dynamics.

---

##  Objectives

- Cluster the Canadian workforce based on weekly earnings, hours worked, education, and demographics.
- Identify hidden patterns of underemployment and low-efficiency labour segments.
- Visualize insights through an interactive Power BI dashboard with 7 drill-down pages.
- Showcase end-to-end data science and BI pipeline for portfolio and job applications.

---

##  Dataset

- **Source:** Statistics Canada - Labour Force Survey (2014–2024)
- **Size:** 100,000+ records | 70+ columns
- **Preprocessing:** Removed 2011 and 2025, dropped >50% null columns, mapped age and education groups, handled outliers using Z-score/IQR.

---

##  Tools & Technologies

- **Languages:** Python (Pandas, Scikit-learn, Seaborn)
- **Visualization:** Power BI (DAX, Slicers, Drill-through)
- **Other Tools:** Excel (Pivot Tables, Data Cleaning)

---

##  Methodology

### 1. **Preprocessing & Feature Engineering**
- Mapped career stages (0–8 years, Mid, Late, etc.)
- Segmented weekly earnings into quantiles (`EARN_GROUP`)
- Calculated **Efficiency Index** = Weekly Earnings / Weekly Hours

### 2. **Clustering (Unsupervised Learning)**
- **Model:** KMeans (K=9)
- **Scaler:** StandardScaler
- **Dimensionality Reduction:** PCA and t-SNE
- **Interpretation:** Cluster profiling by education, hours, and wage

### 3. **Exploratory Data Analysis**
- Cluster distribution by province, gender, education, and earnings
- Created summary tables using Excel Pivot
- Derived provincial efficiency indexes

---

## 📈 Power BI Dashboard (7 Pages)

1. **Workforce by Career Stage**
2. **Earnings vs Hours by Cluster**
3. **Cluster Demographics (Age, Gender)**
4. **Education vs Clusters**
5. **Province-wise Cluster Spread**
6. **Earning Group Segments**
7. **Cluster Drill-Through Explorer**

Each page includes slicers, tooltips, and interactive visuals.

---

## 💡 Key Findings

- **Cluster 0 & 2**: High-earning, highly educated, efficient segments.
- **Cluster 6**: Underemployed group with lowest hours and efficiency.
- **Clusters 7 & 8**: "Working poor" — vulnerable segments with low wages.
- **Geographic Gaps**: PEI, NL show structural underemployment.
- **Education Alignment**: Bachelor's/Grad degrees dominate high-value clusters.

---

## 📌 Use Cases

- Government policy planning for labour support
- Employment agency job-matching systems
- Education-to-wage alignment analytics
- Resume-ready portfolio and Power BI visualization

---

##  Files Included

- `LFS_Clustering.ipynb`: Python clustering script
- `lfs_final.csv`: Cleaned dataset
- `LFS Analysis.pbix`: Full Power BI dashboard
- `README.md`: This document
- `Lfs Analysis Summary.pdf`: Full project write-up

---

## 📅 Duration

- **Timeline:** 2 weeks
- **Project Type:** Independent portfolio project

---

##  Contact

**Guru Prasad Srinivasan**  
[LinkedIn](https://www.linkedin.com/in/guruprasad21) | [GitHub](https://github.com/Guru9840)

---

> 💡 *This project will be extended to predictive modeling using Random Forest to identify at-risk job groups in the Canadian labour market.*

