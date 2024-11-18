# Loan Defaulter Analysis: Insights and Recommendations

**Data Source**: [Kaggle - Loan Defaulter Dataset](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter)

## Analysis Overview

This analysis examines customer data to identify safe segments for loan disbursement and risk-prone areas. The goal is to minimize default rates while optimizing loan approvals.

---

### **Key Insights**

#### 1. **Loan and Default Trends**
- **Cash loans** dominate the loan portfolio and are less likely to default.
- **Unaccompanied individuals** take most loans; their default rate (~8.5%) is within acceptable limits.
- **High default professions**: Low-skill laborers and drivers.
- **Safer professions**: Accountants, Core Staff, Managers, and Laborers (default rate ≤ 7.5–10%).

#### 2. **Demographic Insights**
- **Gender**: Most loans are taken by females; default rate for females is safer (~7%).
- **Education**: Highly educated individuals have a default rate < 5%.
- **Family**: Married individuals are safer targets (default rate ~8%).
- **Housing**: Owning a house/apartment correlates with a safer default rate (~8%).

#### 3. **Income and Credit Insights**
- Safer income groups: Working professionals, Commercial associates, and Pensioners.
- Income below **1 million** is more likely to default for loans ≤ 1.5 million.

#### 4. **Previous Loan Data**
- Applications for **repair purposes** had high cancellation rates previously.
- **80–90% of customers** whose loans were canceled/refused in the past are now repayers.
- Previous **unused offers** correlate with current high default rates, despite high-income bands.

---

### **Recommendations**

#### **Target Customer Segments**
- **Income**: Below **1 million**.
- **Occupation**: Accountants, Core Staff, Managers, Laborers; working in Business Entity Type 3 or as Self-Employed.
- **Demographics**:
  - Gender: Females (preferred).
  - Family: Married individuals with ≤ 5 children.
  - Housing: House/Apartment owners.
  - Education: Highly educated.

#### **Loan Amount and Terms**
- **Credit Amount**: ≤ 1 million.
- **Annuity Payment**: Set at ~50K (depending on eligibility).
- **Income Bracket**: ≤ 1 million.

#### **Special Observations**
- Consider **unaccompanied individuals** (default rate ~8.5%).
- Encourage customers with **previously canceled/refused loans** as they now show strong repayment behavior (80–90%).

---

This document serves as a guide for developing a strategic framework for safer and more profitable loan disbursement practices.
