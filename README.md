# east-sumba-socio-economic-clustering
1st Winner Project: Socio-Economic &amp; Renewable Energy Clustering in East Sumba using Fuzzy Possibilistic C-Means (FPCM).
# Socio-Economic & Renewable Energy Clustering – East Sumba

🏆 **1st Winner & Best Analysis**
**National Poisson Statistics Competition 2025**
Politeknik Statistika STIS

---

## Project Overview

This project analyzes **socio-economic and renewable energy potential in East Sumba** using advanced clustering techniques to support **data-driven regional policy**.

Regional development data often contains **extreme values (outliers)** that can distort traditional clustering methods such as K-Means. To address this issue, the analysis implements **Fuzzy Possibilistic C-Means (FPCM)**, a robust clustering method that reduces sensitivity to outliers while capturing uncertainty in cluster membership.

The final results provide **regional typologies** that can assist policymakers in identifying development priorities and renewable energy opportunities.

---

## Key Features & Methodology

### 1. Robust Regional Clustering

The project applies **Fuzzy Possibilistic C-Means (FPCM)** to group districts based on socio-economic and infrastructure indicators.
Compared with traditional clustering methods, FPCM:

* Handles **noise and outliers** more effectively
* Allows **partial membership** of data points in multiple clusters
* Produces **more stable regional classifications**

---

### 2. Determinant Analysis

To understand **which variables drive cluster formation**, a **Random Forest model** was used.

Key finding:

> **Dependence on the agricultural sector** emerged as the most influential factor differentiating regional clusters.

This helps explain structural disparities between districts in East Sumba.

---

### 3. Interactive Visualization

To improve accessibility for policymakers, the results were deployed into an **Interactive HTML Dashboard**.

Features include:

* Cluster membership visualization
* Socio-economic indicator comparison
* Regional profiling
* Policy-oriented interpretation

---

## Technical Highlights

The FPCM model minimizes the following objective function:

$$
J = \sum_{i=1}^{c} \sum_{j=1}^{n} (u_{ij}^m + t_{ij}^{\eta}) d^2(x_j, a_i)
$$

Where:

- $u_{ij}$ : membership degree of data point $j$ in cluster $i$  
- $t_{ij}$ : possibilistic membership  
- $m$ : fuzziness parameter  
- $\eta$ : possibilistic exponent  
- $d(x_j,a_i)$ : distance between data point and cluster center  

This formulation allows the model to **reduce the influence of noisy observations**.

---

## Methodological Pipeline

1. Data preprocessing and cleaning
2. Multivariate outlier detection (Mahalanobis Distance)
3. Multicollinearity testing (Variance Inflation Factor)
4. Clustering using **Fuzzy Possibilistic C-Means**
5. Cluster validation using:

   * Partition Coefficient (PC)
   * Partition Entropy (PE)
   * Modified Partition Coefficient (MPC)
6. Cluster profiling and interpretation
7. Validation using **Linear Discriminant Analysis (LDA)**
8. Determinant analysis with **Random Forest Variable Importance**

---

## Tools & Technologies

**Programming Languages**

* R
* Python

**Libraries**

* ppclust
* fclust
* randomForest
* pandas
* scikit-learn

**Visualization**

* HTML Dashboards
* R Shiny

---

## Key Outcomes

* Identification of **regional development clusters**
* Understanding of **key socio-economic drivers**
* Data-driven support for **renewable energy planning**
* Robust clustering framework suitable for **policy analysis**

---

## Author

Ryan Sebastian * Rizqi Adika 
Statistics / Data Science

---

## Competition Recognition

🏆 **1st Place & Best Analysis**
National Poisson Statistics Competition 2025
Politeknik Statistika STIS

---

## Topics

`data-science`
`statistics`
`clustering`
`fpcm`
`renewable-energy`
`regional-analysis`
