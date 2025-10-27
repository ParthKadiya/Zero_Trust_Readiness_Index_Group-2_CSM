# Weight Calculation for Zero Trust Readiness Index (ZTRI)

## Objective
The goal of this section is to calculate the **normalized weights** for each of the eight Zero Trust dimensions based on their frequency across 10 reviewed research papers. These weights represent the **relative importance** of each dimension in determining overall Zero Trust readiness.

---

## Step 1: Frequency Data Collection
A total of **10 Zero Trust–related research papers** were reviewed using the Systematic Literature Review (SLR) approach.  
Each paper was analyzed for the occurrence of eight common Zero Trust dimensions.  
Only **Critical**, **High**, and **Medium** mentions were counted for frequency.

| Dimension | Frequency |
|------------|------------|
| Identity | 137 |
| Endpoints | 62 |
| Applications | 92 |
| Infrastructure | 64 |
| Data | 111 |
| Networks | 90 |
| Visibility & Analytics | 46 |
| Automation & Orchestration | 28 |
| **Total** | **630** |

---

## Step 2: Normalization Formula
Each dimension’s frequency was divided by the **total frequency (630)** to convert it into a normalized weight value.

**Weight = Dimension_Frequency / 630**

---

## Step 3: Calculated Normalized Weights
Weights were rounded to **two decimal places** for clarity and consistency.

| Dimension | Frequency | Weight |
|------------|------------|--------|
| Identity | 137 | 0.22 |
| Endpoints | 62 | 0.10 |
| Applications | 92 | 0.15 |
| Infrastructure | 64 | 0.10 |
| Data | 111 | 0.18 |
| Networks | 90 | 0.14 |
| Visibility & Analytics | 46 | 0.07 |
| Automation & Orchestration | 28 | 0.04 |
| **Total** | **630** | **≈ 1.00** |

---

## Step 4: Interpretation
- The **Identity** and **Data** dimensions carry the **highest weight**, indicating that identity management and data protection are the most emphasized components of Zero Trust across academic literature.  
- **Automation & Orchestration** and **Visibility & Analytics** received lower weights, implying that while they are essential, they are less frequently highlighted as core readiness factors in existing research.  
- The final weights sum to approximately **1.00**, confirming correct normalization.

---

## Summary
The normalized weights derived here serve as the foundation for the **ZTRI Scoring Model**, where each dimension’s score (0–5) is multiplied by its respective weight to compute the overall readiness score.

---

✅ **Output Used In:**  
- `/excel-model/ZTRI_Scoring_Model_v1.xlsx`  
- `/docs/02_Readiness_Scoring_Logic.md`

