# 🏀 Causal Analysis of NIL Policy Impact on NCAA Basketball Performance

This project was completed as part of a live case engagement with the **Carlson Analytics Lab**. The objective was to evaluate the causal impact of the NCAA’s **Name, Image, and Likeness (NIL)** policy, introduced in July 2021, on college basketball player performance. The analysis applied advanced causal inference techniques and custom performance metrics to deliver actionable insights for universities, student-athletes, and policy stakeholders.

---

## 🎯 Project Objective

- Quantify the effect of NIL policy implementation on NCAA basketball performance.
- Compare performance outcomes between **U.S. athletes** (exposed to NIL) and **Canadian athletes** (not exposed).
- Identify differential impacts across **player tiers**, **roles**, and **state-level NIL environments**.

---

## 📊 Analytical Approach

The project employed a combination of causal inference methodologies and domain-specific metric design to isolate the effect of NIL from confounding variables:

- **Difference-in-Differences (DiD)** regression with treatment-control (U.S. vs. Canada) and pre-post policy implementation periods.
- **Propensity Score Matching (PSM)** to account for covariate imbalance across comparison groups.
- **Custom performance metrics** to ensure policy-sensitive, role-adjusted analysis:

  - **Adjusted Performance Efficiency Rating (APER):**  
    `APER = (Points + Rebounds + Assists + Steals + Blocks − Turnovers) / Minutes`

  - **Simple LeBRON Score (role-adjusted efficiency):**  
    `Simple LeBRON = PrimaryMetric × 4 + (Steals/min × 2) + (Blocks/min × 1.5) − (Turnovers/min × 3)`  
    *PrimaryMetric is role-specific: AST for Playmakers, PTS for Wings, REB for Bigs.*

---

## 🧠 Key Findings

- A **statistically significant increase** in APER was observed among U.S. athletes post-NIL, indicating a positive policy impact on performance.
- **Wings** (scoring roles) experienced the most substantial gains, suggesting a possible link between NIL-driven visibility and performance enhancement.
- **Lower-tier players** showed greater volatility in response to NIL, pointing to potential inequities in access or benefit.
- Notable **state-level variation** in performance impact was identified, highlighting the importance of localized NIL infrastructure and institutional support.

---

## 🛠️ Tools and Techniques

- **Languages & Libraries:** Python (Pandas, Statsmodels, Scikit-learn)
- **Analytical Methods:** Difference-in-Differences, Propensity Score Matching, Metric Engineering
- **Focus Areas:** Causal Inference, Sports Analytics, Policy Impact Evaluation

---

## 🔐 Confidentiality Notice

> Due to data usage restrictions and the secure nature of the virtual environment in which the analysis was conducted, the source code and presentation materials are not included in this repository. This summary provides a high-level overview of the project’s methodology and insights.
