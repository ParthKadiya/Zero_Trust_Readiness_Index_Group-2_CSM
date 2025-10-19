# 🧠 Developing a Zero Trust Readiness Index (ZTRI) to Measure Enterprise-wide Zero Trust Adoption

## 📘 Overview
This repository presents the research and supporting data for the paper **“Developing a Zero Trust Readiness Index (ZTRI) to Measure Enterprise-wide Zero Trust Adoption.”**  
The study introduces a structured, quantifiable framework to evaluate organizational readiness for Zero Trust implementation across eight core dimensions of cybersecurity maturity.

The ZTRI model builds on insights from **ten academic and industry research papers** through a **Systematic Literature Review (SLR)** approach.  
By transforming qualitative findings from prior works into a **quantitative weighted readiness index**, this project provides a reproducible and evidence-based method to assess how far an enterprise has progressed toward Zero Trust adoption.

---

## 🎯 Research Objective
The primary goal of this research is to establish a **measurable Zero Trust Readiness Index (ZTRI)** capable of quantifying the maturity of organizational Zero Trust initiatives.  
It seeks to answer:
- What are the most critical dimensions influencing Zero Trust adoption?
- How can these qualitative factors be represented numerically to produce a readiness score?

---

## 🧩 Methodology
This research applies a **Systematic Literature Review (SLR)** across ten selected academic and industry publications that address Zero Trust Architecture (ZTA), maturity models, and readiness assessment frameworks.

**Key methodological steps:**
1. **Systematic Review (SLR):** Identification and analysis of 10 peer-reviewed and authoritative sources on Zero Trust maturity and CSF frameworks.  
2. **Frequency-based Weighting:** Extraction of mentions and significance of each of the eight Zero Trust dimensions across all papers.  
3. **Normalization:** Conversion of total frequency counts into proportional weights that sum to 1.0.  
4. **Readiness Scoring:** Application of a 1–5 Likert scale (Non-existent → Optimized) to rate organizations, combined with weighted values to compute an overall readiness score.

**Eight Zero Trust Dimensions:**
- Identity  
- Endpoints  
- Applications  
- Infrastructure  
- Data  
- Networks  
- Visibility & Analytics  
- Automation & Orchestration  

---

## 💡 Novelty and Contribution
This research extends the foundational work of **Yeoh et al. (2023)** — *“Zero Trust Cybersecurity: Critical Success Factors and a Maturity Assessment Framework”* — by transforming its **qualitative Delphi-based model** into a **quantitative scoring matrix**.

**Novel Contributions:**
- Introduces a **Zero Trust Readiness Index (ZTRI)** combining SLR-based weights with quantitative scoring.  
- Translates theoretical maturity factors into **measurable organizational indicators**.  
- Enables practitioners and researchers to compare readiness levels across industries using standardized metrics.  

The ZTRI framework thus bridges the gap between **academic Zero Trust theory** and **practical enterprise assessment**.

---

## 🧮 How to Use
1. Open the included Excel file: `ZTRI_Scoring_Calculation.xlsx`.  
2. For each of the eight dimensions, assign a readiness score from **1 (Non-existent)** to **5 (Optimized)**.  
3. The weighted score and overall readiness index will be calculated automatically.  
4. The resulting **ZTRI value (0–5)** represents the organization’s overall Zero Trust maturity level.

---

## 🧾 References

1. Abbas, H., & Ahmed, M. (2025). *A Survey of Security in Zero Trust Network Architectures.* **IEEE Access**, 13, 15502–15524.  
2. Nymalm, A. (2025). *Zero Trust Threat Modeling: STRIDE-ZTA.* Master’s Thesis, Metropolia University of Applied Sciences.  
3. Gartner Research. (2025). *Emerging Technologies Driving Zero Trust Maturity Across Industries.* *Gartner Insights White Paper.*  
4. Ali, H., & Khan, A. (2022). *A Maturity Framework for Zero-Trust Security in Multi-Access Edge Computing.* **Security and Communication Networks**, 2022, 1–15. [https://doi.org/10.1155/2022/9826314](https://doi.org/10.1155/2022/9826314)  
5. National Institute of Standards and Technology (NIST). (2024). *Cybersecurity Framework 2.0 – Incorporating Zero Trust Principles (NIST CSWP 2.9).* *U.S. Department of Commerce*, Gaithersburg, MD.  
6. Cybersecurity and Infrastructure Security Agency (CISA). (2023). *Zero Trust Maturity Model v2.* *U.S. Department of Homeland Security.*  
7. Microsoft Corporation. (2024). *AI and Zero Trust Roadmap: A Strategic Implementation Guide.* *Microsoft White Paper.*  
8. Kindervag, J. (2018). *Forrester Zero Trust eXtended (ZTX) Ecosystem.* *Forrester Research.*  
9. National Institute of Standards and Technology (NIST). (2020). *Special Publication 800-207: Zero Trust Architecture.* *U.S. Department of Commerce*, Gaithersburg, MD. [https://doi.org/10.6028/NIST.SP.800-207](https://doi.org/10.6028/NIST.SP.800-207)  
10. Yeoh, W., Liu, M., Shore, M., & Jiang, F. (2023). *Zero Trust Cybersecurity: Critical Success Factors and a Maturity Assessment Framework.* **Computers & Security**, 133, 103412. [https://doi.org/10.1016/j.cose.2023.103412](https://doi.org/10.1016/j.cose.2023.103412)  
