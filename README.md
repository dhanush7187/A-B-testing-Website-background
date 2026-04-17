# A/B Testing Analysis – UI Optimization Project

## Overview  
This project presents an end-to-end A/B testing analysis conducted on a dataset of 5,000+ users to evaluate the impact of a UI change (website background color) on conversion rates. The goal was to determine whether the design modification leads to a statistically significant improvement in user conversions.

---

## Objective  
- Compare performance between **Control Group (White Background)** and **Variant Group (Black Background)**  
- Measure impact on key metrics:
  - Conversion Rate  
  - Time Spent  
  - Page Views  
- Validate results using statistical hypothesis testing  

---

## Dataset  
- **Total Users:** 5,000+  
- **Group A (Control – White):** 2,519 users  
- **Group B (Variant – Black):** 2,481 users  

**Features:**
- User ID  
- Group  
- Conversion (Yes/No)  
- Time Spent  
- Page Views  
- Device Type  
- Location  

---

## Tools & Technologies  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy, Statsmodels  

---

## Methodology  
1. Data Cleaning & Exploratory Data Analysis (EDA)  
2. Conversion Rate Analysis  
3. Data Visualization (Bar charts, Box plots, Heatmaps)  
4. Hypothesis Testing:
   - Chi-Square Test  
   - Z-Test for Proportions  
   - Z-Test for Means  

---

## Key Results  
- Conversion Rate increased from **5.40% → 14.07% (~160% uplift)**  
- Highly significant statistical result:
  - **p-value: 6.57e-25**  
- No significant change observed in:
  - Time Spent  
  - Page Views  

---

## Insights  
- UI change significantly improves user conversion behavior  
- Increased conversions are not driven by longer sessions or more browsing  
- Indicates a more **action-oriented user experience**  

---

## Conclusion  
The experiment provides strong statistical evidence that the **black background (Variant B)** significantly improves conversion rates compared to the control.

---

## Recommendation  
Deploy the variant (black background) to production, as it delivers a substantial and statistically significant improvement in conversions.

---

