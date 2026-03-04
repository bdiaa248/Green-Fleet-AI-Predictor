# 🌿 Green Fleet AI Predictor
**Strategic AI Solution for Sustainable Government Fleet Procurement**

##  Business Challenge
A government agency must renew its vehicle fleet while staying under strict environmental carbon limits. Failure to comply results in severe legal penalties. 

The goal of this project is to build an AI-driven predictive system capable of estimating the CO₂ emissions of new vehicle models before procurement, ensuring full regulatory compliance.

---

##  Exploratory Data Analysis

### 1. CO₂ Emissions Distribution
Understanding how emissions are distributed across the dataset helps identify typical emission ranges and potential outliers.

> *Note: Insert your histogram image here*
> `![CO2 Emissions Distribution](link-to-your-image.png)`

This visualization shows that most vehicles fall within a moderate emissions range, while a smaller group of high-emission vehicles appears as a right-side tail.

### 2. Feature Correlation Analysis
To build an accurate prediction model, it is important to understand how variables relate to each other.

> *Note: Insert your correlation matrix heatmap here*
> `![Feature Correlation Matrix](link-to-your-image.png)`

**Key insights from the correlation matrix:**
* **City fuel consumption** strongly correlates with CO₂ emissions.
* **Combined MPG** shows a strong negative correlation with emissions.
* **Engine size** also contributes significantly to emission levels.

These relationships guided the feature selection process for the predictive model.

---

##  Tech Stack & Skills Demonstrated

**Languages & Libraries:**
* **Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels

**Analytical Techniques:**
* Exploratory Data Analysis (EDA)
* Hypothesis Testing (Welch's T-test)
* Feature Selection
* Simple & Multiple Linear Regression
* Multicollinearity Handling (Dummy Variable Trap)

---

##  Project Pipeline

1.  **Statistical Trial:** Executed Welch's T-test to confirm that compact vehicles produce statistically lower CO₂ emissions compared to mid-size vehicles.
2.  **Strategic Feature Selection:** City fuel consumption was prioritized over combined fuel consumption due to the agency’s operational focus on urban environments.
3.  **Multivariate AI Modeling:** A Multiple Linear Regression model was trained using engineered categorical variables.
4.  **Prediction System:** A custom prediction function was developed to evaluate unseen candidate vehicles before procurement decisions are made.

---

##  Model Performance
* **R² Score:** `0.979`
* *Interpretation:* The model explains approximately 97.9% of the variance in CO₂ emissions, demonstrating exceptional predictive accuracy.

---

##  Final Procurement Verdict

Based on model predictions, the candidate vehicles were ranked strictly on environmental compliance and strategic viability:

| Vehicle Model | Predicted CO₂ (g/km) | Strategic Status |
| :--- | :--- | :--- |
| **2023 Honda Accord** | 161.85 | ✅ Highly Recommended |
| **2024 Nissan Sentra** | 197.85 | ⚠️ Marginal Compliance |
| **2023 Kia Forte** | 213.25 | ❌ Not Recommended |
| **2024 Genesis G70** | 280.63 | 🚫 Rejected |

###  Final Recommendation
The **2023 Honda Accord** provides the optimal balance between operational efficiency and environmental compliance.

---

## 👨‍💻 Author
**Diaa Shousha** *AI & GeoAI Engineer* Specializing in applied AI systems and spatial intelligence.
