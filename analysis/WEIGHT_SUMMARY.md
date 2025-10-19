# Zero Trust Weight Derivation Summary

## Introduction
This section tell about the **weight derivation of the eight Zero Trust dimensions** based on a systematic review of ten research papers.  
Frequencies of dimension mentions were calculated and normalized to a total of **1.0** to shows their importance in Zero Trust research.  
These normalized values form the **Zero Trust Readiness Index (ZTRI)** model, which measures an organization’s overall maturity through **weighted scoring**.

---

## Normalized Weight Summary

| **Dimension** | **Weight** | **Interpretation** |
|----------------|-------------|--------------------|
| **Identity** | 0.217 | Identity emerged as the most dominant dimension across all reviewed literature, emphasizing strong authentication, access governance, and user verification as the foundation of Zero Trust readiness. |
| **Endpoints** | 0.098 | Endpoints reflect device management, EDR, and compliance visibility. While secondary, they remain critical for preventing lateral movement and enforcing trust per session. |
| **Applications** | 0.146 | Applications represent secure workloads and adaptive access policies. They demonstrate significant importance as organizations increasingly depend on SaaS and cloud-based applications. |
| **Infrastructure** | 0.102 | Infrastructure relates to the Zero Trust Architecture backbone, including SDN, virtualization, and policy enforcement points. It serves as an enabler for cross-layer controls. |
| **Data** | 0.176 | Data holds the second-highest weight, highlighting data-centric protection, encryption, and DLP. Most research positions data as the *“ultimate perimeter”* in Zero Trust. |
| **Networks** | 0.143 | Networks retain a traditional but critical role, focusing on segmentation, micro-perimeters, and encrypted traffic. They act as enforcement zones for identity and policy decisions. |
| **Visibility & Analytics** | 0.073 | Visibility and analytics were moderately weighted but central to maturity progress—organizations require behavioral analytics and telemetry for continuous trust validation. |
| **Automation & Orchestration** | 0.044 | Automation and orchestration, though the lowest weighted, are recognized as future enablers. They ensure scalability, consistency, and self-healing security operations. |

---

## Analytical Interpretation
From the results, **Identity (0.217)** and **Data (0.176)** together make up almost **40%** of the total importance.  
This shows that they are the **two most important parts** of Zero Trust maturity. These areas often appear in serious topics like **authentication, access control, and data protection**.

**Applications (0.146)** and **Networks (0.143)** come next. They show how cybersecurity is moving away from old perimeter-based methods and toward **smarter, context-aware protection** that focuses on specific workloads and access needs.  
**Infrastructure (0.102)** supports these layers as the main **technical base** that keeps everything connected and secure.

**Automation & Orchestration (0.044)**, although mentioned the least, are becoming more important in **new frameworks** such as **CISA ZTMM v2** and **NIST CSWP 2.0**. They help make systems more **scalable, consistent, and self-managing**.

The total weight adds up to **1.0**, which means all eight dimensions are **fairly balanced**.  
These findings give a **strong starting point** for calculating **Weighted Readiness Scores** in the **ZTRI model**, helping both researchers and organizations measure their Zero Trust maturity in a clear and practical way.

