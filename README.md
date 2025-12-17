# 📊 A/B Testing: Facebook vs. AdWords Ad Campaign Analysis

## 🧠 Business Problem
As a marketing agency, we aim to maximize ROI for our clients by identifying which advertising platform—**Facebook** or **AdWords**—delivers better performance in terms of clicks, conversions, and cost-effectiveness. By analyzing campaign data from 2019, we evaluate which platform deserves more budget allocation.

---

## ❓ Research Question
**Which ad platform is more effective in terms of:**
- Conversions
- Clicks
- Overall Cost-Effectiveness

---

## 🗃️ Dataset Overview
The dataset includes 365 daily records for the year 2019 with the following key features:
- **Ad Views**, **Clicks**, **Conversions** for both Facebook and AdWords
- **Cost per Ad**, **Click-Through Rate (CTR)**, **Conversion Rate**, and **Cost per Click (CPC)**

---

## 🛠️ Tools & Libraries Used
- **Python**: Data analysis
- **Pandas, NumPy**: Data wrangling
- **Matplotlib, Seaborn**: Data visualization
- **SciPy, Statsmodels**: Statistical testing and time series analysis
- **Scikit-learn**: Regression modeling

---

## 🔍 Key Analyses & Findings

### 📈 Performance Distributions
- Facebook had more high-conversion days (`10–15+`) than AdWords.
- AdWords conversions were mostly in the `6–10` or `less than 6` range.

### 🔗 Correlation Analysis
- **Facebook Clicks ↔ Conversions:** Strong correlation (0.87)
- **AdWords Clicks ↔ Conversions:** Moderate correlation (0.45)

### 🧪 Hypothesis Testing
- **H₀:** Facebook conversions ≤ AdWords conversions  
- **Result:** **Rejected** — Facebook has significantly more conversions (p-value ≈ 0)

### 📉 Regression Modeling
- R² Score: **76.35%**  
- Predicts expected Facebook conversions based on number of clicks.

### 📆 Time Trends
- **Highest conversions:** Mondays and Tuesdays
- **Most cost-effective months:** May and November (lowest CPC)

### ⚖️ Cointegration Test
- Found a **long-term equilibrium** between Facebook Ad Spend and Conversions.
- Indicates a stable relationship useful for **budget optimization**.

---

## 📌 Business Recommendations
- Reallocate more budget to **Facebook** ads for higher conversions.
- Focus on **Mondays/Tuesdays** and **low-CPC months (May, Nov)**.
- Consider **regression forecasting** to set performance goals.
- Use cointegration insights to optimize long-term ad spend strategy.

---


