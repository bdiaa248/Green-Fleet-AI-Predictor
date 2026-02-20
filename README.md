# 🌿 Green Fleet AI Predictor

**Strategic AI Solution for Sustainable Government Fleet Procurement**

## Business Challenge
A government agency must renew its vehicle fleet while staying under strict environmental carbon limits. Failure to comply results in severe legal penalties. The goal of this project is to build an AI-driven predictive system to estimate the CO₂ emissions of new car models *before* procurement, ensuring 100% policy compliance.

## Tech Stack & Skills Demonstrated
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels
* **Statistical Analysis:** Hypothesis Testing (Welch's T-test)
* **Machine Learning:** Exploratory Data Analysis (EDA), Feature Selection, Simple & Multiple Linear Regression
* **Data Engineering:** Categorical encoding, handling the Dummy Variable Trap (Multicollinearity)

## Project Pipeline
1. **Statistical Trial:** Executed Welch's T-test to prove Compact vehicles produce significantly lower emissions compared to Mid-size vehicles.
2. **Strategic Feature Selection:** Prioritized 'City' fuel consumption over 'Combined' based on the operational reality of the client (urban traffic).
3. **Multivariate AI Modeling:** Built a Multiple Linear Regression model incorporating engineered categorical variables (Fuel Type), achieving a remarkable **R-squared of 97.9%**.
4. **Prediction & Actionable Insight:** Deployed a custom prediction function to evaluate a shortlist of unseen candidate vehicles.

## 🏆 Final Procurement Verdict
Based on the AI model's precise predictions, the vehicles were ranked as follows:

| Vehicle Model | Predicted CO₂ (g/km) | Strategic Status |
| :--- | :--- | :--- |
| **2023 Honda Accord** | **161.85** | ✅ **Highly Recommended (Winner)** |
| 2024 Nissan Sentra | 197.85 | ⚠️ Marginal Compliance |
| 2023 Kia Forte | 213.25 | ❌ Not Recommended |
| 2024 Genesis G70 | 280.63 | 🚫 **REJECTED** (Worst Offender) |

**Conclusion:** The agency is officially advised to procure the **2023 Honda Accord** to meet carbon targets and maximize operational efficiency.

---
*Developed by Abdelrahman Diaa (Diaa Shousha) - AI & GeoAI Engineer*
