# PCA and t-SNE Vehicle Segmentation

## Overview
This project explores patterns in vehicle characteristics using dimensionality reduction and clustering techniques. The goal is to better understand how cars differ based on engine size, weight, horsepower, fuel efficiency, and model year, and to identify natural groupings within the data.

The analysis focuses on exploration and interpretation rather than prediction.

---

## Dataset
The dataset contains technical specifications for vehicles produced between 1970 and 1982, including:
- MPG (fuel efficiency)
- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model year

**Note:** The raw dataset is not included in this repository due to course usage restrictions.

---

## Methods Used
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Correlation analysis  
- Feature scaling  
- Principal Component Analysis (PCA)  
- KMeans clustering in PCA space  
- t-SNE for nonlinear visualization  

---

## Key Insights
- Engine-related features such as weight, displacement, horsepower, and cylinders are strongly correlated and describe overall vehicle size and power.
- PCA effectively reduces redundancy while preserving the main structure of the data.
- Vehicles naturally group into three broad segments:
  1) Larger, more powerful vehicles with lower fuel efficiency  
  2) Mid-sized vehicles with balanced characteristics  
  3) Smaller, lighter vehicles with higher fuel efficiency  
- Fuel efficiency tends to improve with newer model years, reflecting gradual technological progress.

---

## Practical Takeaways
This segmentation helps clarify how different types of vehicles relate to different customer preferences. Some drivers prioritize performance and engine power, while others value fuel efficiency and practicality. These insights can support clearer positioning and communication around different vehicle types.

---

## Tools & Libraries
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn
