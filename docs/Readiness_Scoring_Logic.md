# Readiness Scoring Logic for Zero Trust Readiness Index (ZTRI)

## Objective
This section explains how organization-specific maturity scores (0–5 scale) are combined with dimension weights to calculate the **overall Zero Trust Readiness Score** and assign a **readiness category**.

---

## Step 1: Scoring Scale (0–5)

Each Zero Trust dimension is scored between **0** and **5** based on the organization’s maturity level.

| Score | Level | Description |
|:------:|:------|:-------------|
| **0** | Non-Existent | No implementation or awareness of Zero Trust principles in this area. |
| **1** | Initial | Basic awareness; limited or ad-hoc efforts. |
| **2** | Basic | Defined goals and partial implementation; lacks consistency. |
| **3** | Intermediate | Structured, repeatable practices exist; measurable progress. |
| **4** | Advanced | Well-implemented and integrated with enterprise security strategy. |
| **5** | Optimised | Continuous monitoring, automation, and Zero Trust fully embedded. |

---

## Step 2: Weighted Scoring Formula

Each dimension’s contribution to readiness is calculated as:

**Weighted Score = Dimension Weight × Dimension Score**

All eight weighted scores are then summed to produce the **Total Readiness Score**:

**Total Readiness Score = Σ (Weight × Score)**

The resulting value will always fall between **0.00** and **5.00**.

---

## Step 3: Example Calculation

| Dimension | Weight | Score | Weighted Score |
|------------|---------|-------|----------------|
| Identity | 0.22 | 4 | 0.88 |
| Data | 0.18 | 3 | 0.54 |
| Applications | 0.15 | 3 | 0.45 |
| Endpoints | 0.10 | 2 | 0.20 |
| Infrastructure | 0.10 | 3 | 0.30 |
| Networks | 0.14 | 4 | 0.56 |
| Visibility & Analytics | 0.07 | 2 | 0.14 |
| Automation & Orchestration | 0.04 | 1 | 0.04 |
| **Total Readiness Score** |  |  | **3.11 / 5** |

---

## Step 4: Readiness Category Mapping

| Total Readiness Score | Category | Description |
|:----------------------:|:----------|:-------------|
| 0.00 – 0.99 | **Non-Existent** | No Zero Trust implementation. |
| 1.00 – 1.99 | **Initial** | Awareness stage; fragmented adoption. |
| 2.00 – 2.99 | **Basic** | Some Zero Trust controls in place but not organization-wide. |
| 3.00 – 3.99 | **Intermediate** | Zero Trust partially integrated; measurable maturity. |
| 4.00 – 4.49 | **Advanced** | Strong, consistent Zero Trust adoption. |
| 4.50 – 5.00 | **Optimised** | Fully mature and automated Zero Trust ecosystem. |

---

## Step 5: Excel Implementation

In the scoring sheet **`/excel-model/ZTRI_Scoring_Model_v1.xlsx`**:

- **Column B:** Weights (pre-filled, locked)  
- **Column C:** User input scores (0–5)  
- **Column D:** Formula → `=B2*C2` (Weighted Score)  
- **Overall Readiness:** `=SUM(D2:D9)`  
- **Readiness Category:**

```excel
=IFS(
    E2<1,"Non-Existent",
    E2<2,"Initial",
    E2<3,"Basic",
    E2<4,"Intermediate",
    E2<4.5,"Advanced",
    E2<=5,"Optimised"
)
```

## Summary

**Input:** 0–5 maturity score per dimension  
**Process:** Multiply by normalized weight  
**Output:** Overall readiness score (0–5) and automatic readiness category  

---

**Used In:** 

- `/excel-model/ZTRI_Scoring_Model_v1.xlsx`
