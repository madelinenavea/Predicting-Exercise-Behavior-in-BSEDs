# Depression-and-Eating-Disorder-Behaviors
Using multiple linear regression to examine how certain depression symptoms predict eating disorder behaviors.

---

**Conference Project Title:** Self-Criticism and Punishment Feelings Predict Driven Exercise at Post-Treatment in Adults with Binge-Spectrum Eating Disorders  
**Authors:** Madeline Navea, Lucy Wetherall, Devyn Riddle, Ross Sonnenblick, Stephanie Manasse, & Adrienne Juarascio  
**Conferences Presented Work At:** Associations for Behavioral and Cognitive Therapies Conference 2024

---

## Overview

This project explores the **predictive power of depressive symptomatology—specifically self-criticism (SC) and punishment feelings (PF)**—on treatment outcomes in individuals with **binge-spectrum eating disorders (BSEDs)**. This project focuses on applying **multiple linear regression models** to clinical data to assess whether baseline SC and PF predict behavioral outcomes following enhanced cognitive behavioral therapy (CBT-E).

---

## Research Questions

- Can baseline **self-criticism** and **punishment feelings**, as measured by BDI-II items, predict post-treatment outcomes in BSED patients?
- Do these predictors hold explanatory power for different behavioral outcomes—e.g., **driven exercise**, **binge eating**, or **vomiting**?
- Can we build a **generalizable model** for early treatment-stage risk profiling?

---

## Data Description

- **Participants:** N = 165 adults with clinically significant BSEDs (≥12 LOC episodes in past 3 months)
- **Demographics:** Mean age = 38.7 (SD = 12.84), 87.3% female, 73.3% white
- **Treatment:** 12–20 CBT-E sessions across 4 studies

### Key Variables

- **Predictors:**
  - Self-Criticism (SC)
  - Punishment Feelings (PF)
- **Covariates:**
  - Gender
  - Study membership
  - Baseline eating disorder pathology
- **Outcomes:**
  - EDE Global Score
  - Total Objective Bulimic Episodes (OBEs)
  - Total LOC Episodes
  - Self-Induced Vomiting Episodes
  - Driven Exercise Days

> **Note**: Data that support the findings of this study are available from the corresponding authors upon reasonable request. Code and data visualizations are available to download.

---

## Methods

- **Modeling Approach:** Multiple linear regression
- **Control Variables:** Study, gender, baseline pathology
- **Evaluation Metrics:** Regression coefficients, p-values, R², residual analysis
- **Tools Used:** `stats`, `tidyverse`, `ggplot`

---

## Key Results

- **Punishment Feelings** (β = 0.782, *p* = 0.031) and **Self-Criticism** (β = -0.816, *p* = 0.024) significantly predicted **increased driven exercise** at post-treatment.
- No significant prediction observed for:
  - EDE Global Score
  - Objective Bulimic Episodes
  - LOC Episodes
  - Self-Induced Vomiting

These findings support the potential clinical utility of early identification and targeted intervention for SC and PF in individuals undergoing CBT-E for BSEDs.

---

## Future Directions

- Apply **nonlinear modeling approaches** (e.g., Random Forests, XGBoost) for robustness checks
- Develop **longitudinal models** to capture symptom trajectories
- Analyze **additional BDI-II subcomponents** for broader predictive insights
- Explore **causal inference** strategies to differentiate correlation from mechanism

---

## Citation

If you use or adapt this repository, please cite the original authors and conference submission:
Navea, M., Wetherall, L., Riddle, D., Sonnenblick, R., Manasse, S., & Juarascio, A. (2024). Self-criticism and punishment feelings predict driven exercise at post-treatment in adults with binge-spectrum eating disorders. Association for Behavioral and Cognitive Therapies (ABCT) 2024.
