# ⚙️ ZTRI Formula Explanation

## Purpose
This file documents the calculation logic behind the **Zero Trust Readiness Index (ZTRI)** to ensure transparency and reproducibility.

---

## 1. Weighted Scoring Formula
Each dimension contributes to the total readiness score based on its normalized weight and assigned score.

```
Weighted Score = Dimension Weight × Dimension Score
```

### Example
```
Identity = 0.22 × 4 = 0.88
Data = 0.18 × 3 = 0.54
...
Total Readiness = 3.11 / 5
```

---

## 2. Total Readiness Formula
All weighted scores are summed to compute the final readiness value.

```
Total Readiness Score = Σ (Weight × Score)
```

Result range: **0.00 to 5.00**

---

## 3. Excel Implementation

| Column | Description | Example |
|--------|--------------|----------|
| B | Weight (pre-filled) | 0.22 |
| C | Score (input 0–5) | 4 |
| D | Weighted Score | `=B2*C2` |
| E | Overall Score | `=SUM(D2:D9)` |

---

## 4. Category Logic (Summary)
The overall readiness score maps to one of six readiness categories defined in `/docs/02_Readiness_Scoring_Logic.md`.

| Score Range | Category |
|--------------|-----------|
| 0.00–0.99 | Non-Existent |
| 1.00–1.99 | Initial |
| 2.00–2.99 | Basic |
| 3.00–3.99 | Intermediate |
| 4.00–4.49 | Advanced |
| 4.50–5.00 | Optimised |

---

## ✅ Output
The result provides:
- Weighted score per dimension  
- Total readiness score  
- Readiness category label
