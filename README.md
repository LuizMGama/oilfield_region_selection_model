# 🛢️ Project: Oilfield Profit Prediction

## 🎯 Project Objective  
The goal of this project is to help the oil company **OilyGiant** select the most profitable region for developing new oil wells.  
To do this, a regression model is trained to predict the volume of reserves per well, and bootstrapping is used to estimate potential profits and risks in each of three regions.

---

## ✅ Results Achieved  
- Performed data exploration and feature inspection across three regions  
- Trained a **Linear Regression** model for each region using reservoir characteristics  
- Calculated RMSE and average predicted production per region  
- Used model predictions to select the 200 most promising wells (from a sample of 500)  
- Applied **bootstrapping (1,000 iterations)** to simulate profits and assess risk  
- Selected the region with:
  - Highest average profit  
  - Loss risk below the 2.5% threshold

---

## 🛠️ Tools and Technologies Used  
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, scikit-learn  
- **Techniques applied:**
  - Regression modeling (LinearRegression)
  - Model validation with train/validation splits
  - Bootstrapping to simulate and evaluate business outcomes
  - Risk assessment using profit distributions

---

## 🚀 Skills Developed  
- Data preparation and exploratory data analysis  
- Predictive modeling for real-world economic scenarios  
- Use of simulation (bootstrapping) to estimate uncertainty and risk  
- Comparison of model performance across multiple datasets  
- Business-driven decision-making based on data science outputs

---

## 🔧 Future Improvements  
- Explore additional regression models (e.g., Ridge or SVR)  
- Optimize well selection using cost constraints or ROI thresholds  
- Include geological context if feature semantics become available  
- Integrate real-time simulation dashboard for investment planning
