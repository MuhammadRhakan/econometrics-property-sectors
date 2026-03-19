# Econometric Analysis on Capital Structure Determinants in the Indonesian Property Sector

## 📌 Project Overview
This repository features an econometric study investigating the impact of Profitability (NPM), Liquidity (CR), and Non-Debt Tax Shields (NDTS) on the Capital Structure (Debt-to-Equity Ratio) of companies in the Indonesian property sector.

A unique focus of this study is the exploration of Firm Size as a moderating variable to determine if company scale alters how financial drivers influence leverage decisions.

## ⚖️ Problem Statement
Despite established financial theories, empirical results in the Indonesian property market remain inconsistent. This study addresses the gap by evaluating whether Firm Size acts as a catalyst or a buffer for these relationships, specifically within firms under special monitoring.

## 🛠️ Data & Methodology
* **Data Source:** Financial statements of property sector firms (IDN Stock Exchange).
* **Variables:**
  - **Dependent:** Debt-to-Equity Ratio (DER).
  - **Independent:** Net Profit Margin (NPM), Current Ratio (CR), Non-Debt Tax Shield (NDTS).
  - **Moderator:** Firm Size (Total Assets).
* **Techniques:** Panel Data Regression, Interaction Effects (Moderation Analysis).

**Econometric Pipeline**
1. **Descriptive Statistics:** Summary of mean, median, and variance.
2. **Classical Assumption Tests:**
    - **Multicollinearity:** Variance Inflation Factor (VIF).
    - **Heteroskedasticity:** Breusch-Pagan / White Test.
    - **Autocorrelation:** Durbin-Watson test.
    - **Normality:** Shapiro-Wilk test for residuals.
3. **Model Selection:** Fixed Effects vs. Random Effects.
4. **Moderation Analysis:** Assessing the interaction terms (e.g., $NPM \times Fimr Size$).

## 📊 Key Findings
* **Key Determinants:** All variables are simultaneously significant in explaining the capital structure. However, in individual settings, only Profitability (NPM) and Non-Debt Tax Shield (NDTS) that exhibit significance, while Liquidity (CR) does not emerge a primary determinant.
* **Firm Size:** Interestingly, size did not significantly moderate the relationships, suggesting consistent financing behavior across small and large firms in this sector.
* **Model Accuracy:** The $R^2$ of 0.3392 indicates that while these factors are relevant, 66% of capital structure variance is driven by external market conditions or unobserved firm-specific factors.
