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
From the gathered results, **Identity (0.217)** and **Data (0.176)** together make up nearly **40% of the total importance**, identifying them as the two main important pillars of Zero Trust maturity.  
These dimensions frequently appear in high-severity contexts such as authentication, access control, and data protection.

**Applications (0.146)** and **Networks (0.143)** closely follow, demonstrating the shift from perimeter-based security toward **context-aware, workload-centric protection**.  
**Infrastructure (0.102)** underpins these layers as the architectural backbone and enforcement framework.

Meanwhile, **Automation & Orchestration (0.044)**, though least frequent, are becoming increasingly important in newer frameworks such as **CISA ZTMM v2** and **NIST CSWP 2.0**, driving scalability and automated cyber resilience.

The **total weight equals 1.0**, ensuring balanced proportional representation across all eight dimensions.  
These results provide a validated baseline for computing **Weighted Readiness Scores** in the **ZTRI model**, supporting both academic evaluation and practical enterprise assessment.
