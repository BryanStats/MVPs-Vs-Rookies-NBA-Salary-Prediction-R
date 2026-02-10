# MVP vs. Rookie: NBA Salary Prediction in R

## 📌 Project Overview
This project applies **statistical modeling** and **machine learning** techniques to identifying the key performance indicators (KPIs) that drive NBA player salaries. Beyond a simple regression, this analysis segments the market to compare how **Rookies** are valued (based on potential/efficiency) versus how **MVPs** are valued (based on volume production).

## 🚀 Key Results
* **Market Segmentation:** Discovered that **Points Per Minute** is a critical predictor for Rookie contracts, while **Total Rebounds** and **Games Started** drive Veteran/MVP value.
* **Model Performance:** Achieved an **Adjusted R-Squared of ~0.54** across the general population, with higher predictive accuracy within segmented clusters.
* **Outlier Analysis:** Successfully predicted high-leverage contracts (e.g., Victor Wembanyama, Joel Embiid) by engineering efficiency features to account for outliers.

## 📂 Project Deliverables
* **[📄 Presentation Slides](Reports/Presentation.pdf):** A high-level deck comparing Rookie vs. MVP salary drivers, designed for non-technical stakeholders.
* **[📝 Technical Report](Reports/Technical_Report.pdf):** The full statistical breakdown, including residual analysis, VIF checks for multicollinearity, and code.

## 🛠️ Technologies Used
* **Language:** R
* **Libraries:** `tidyverse`, `ggplot2`, `caret`, `car` (ANOVA/VIF)
* **Statistical Methods:** Multiple Linear Regression, Stepwise Selection (AIC/BIC), Log-Transformation, Cook's Distance.

## 💻 How to Run

1. **Clone the repository:**
   * [MVPs Vs Rookies NBA Salary Prediction - GitHub](https://github.com/BryanStats/MVPs-Vs-Rookies-NBA-Salary-Prediction-R.git)
    * **install.packages(c("tidyverse", "car", "caret", "ggplot2"))**
