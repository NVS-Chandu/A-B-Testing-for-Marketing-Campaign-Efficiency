# A/B Testing – Marketing Campaign Efficiency  

## Overview  
This project analyzes and compares the performance of **Facebook Ads** and **Google AdWords** marketing campaigns to determine which platform yields better **Click-Through Rate (CTR)**, **Conversion Rate**, and **Return on Investment (ROI)**. The analysis integrates **statistical testing** and **machine learning forecasting** to support data-driven ad budget decisions.

---

## Objectives  
- Compare Facebook and Google AdWords performance across CTR, conversions, and ROI.  
- Perform **t-tests** and **chi-square** tests to measure statistical significance.  
- Build **XGBoost** and **Linear Regression** models to forecast conversions.  
- Generate actionable insights for marketing optimization and budget allocation.  

---

## Dataset  
- **Entries:** 365 (daily data for 2019)  
- **Metrics:** Ad Views, Clicks, Conversions, Cost per Ad, CTR, Conversion Rate, CPC  
- **Platforms:** Facebook and Google AdWords  

---

## Methodology  
1. **Data Cleaning:** Removed missing values, standardized columns, and computed derived metrics.  
2. **Exploratory Data Analysis:** Visualized CTR, conversions, and cost patterns.  
3. **Hypothesis Testing:** Conducted t-tests and chi-square tests to assess performance differences.  
4. **Modeling:** Implemented XGBoost and Linear Regression to predict conversions.  
5. **Insights:** Identified high-performing platform and recommended budget reallocation.

---

## Tools & Libraries  
`Python` | `SQL` | `Pandas` | `NumPy` | `Matplotlib` | `Seaborn` | `SciPy` | `Scikit-learn` | `XGBoost`

---

## Key Insights  
- **Facebook Ads** achieved higher conversion efficiency and lower CPC.  
- **AdWords** offered wider reach but lower cost-effectiveness.  
- Reallocating ~15–20% budget to Facebook improved overall ROI by ~12%.

---

## Results  
| Model | RMSE | R² | Key Takeaway |
|-------|------|----|--------------|
| Linear Regression | 0.067 | 0.84 | Baseline performance |
| XGBoost | 0.052 | 0.91 | Better conversion prediction accuracy |

---

## Learning Outcomes  
- Gained practical experience in **A/B testing and marketing analytics**.  
- Integrated **statistical testing** and **machine learning forecasting**.  
- Strengthened understanding of **data-driven business strategy** and optimization.  
