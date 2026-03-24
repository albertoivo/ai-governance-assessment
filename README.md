# Cleared for Launch: AI Governance Assessment
## ClinicalCompanion — MedAssist AI

This repository contains a comprehensive AI governance assessment for **ClinicalCompanion**, a generative AI clinical decision support system preparing for EU market launch.

---

## Overview

ClinicalCompanion is a clinical decision support system (CDSS) that uses generative AI to analyze patient records and provide diagnostic suggestions to physicians. This assessment evaluates the system's readiness across regulatory compliance, risk management, vendor governance, model documentation, and post-deployment monitoring.

The assessment covers:
- **EU AI Act Classification**: Risk classification and compliance gap analysis.
- **NIST AI Risk Management**: Risk identification, assessment, and mitigation visualization.
- **Vendor Governance**: Evaluation of foundation model providers across ethical and security dimensions.
- **Model Card documentation**: Disaggregated performance analysis by subgroup (fairness analysis).
- **Post-Deployment Monitoring**: Design of a 4-panel monitoring dashboard for KPIs and incidents.

---

## Assessment Workflow

The assessment was performed across 8 core steps to ensure ClinicalCompanion meets all regulatory and safety standards:

**Step 1: System Specification Analysis**
Analysis of system architecture, foundation model details (FoundationHealth LLM v3.2), and training data sources.

**Step 2: EU AI Act Risk Classification**
Detailed classification based on Article 5 (Prohibited Practices) and Article 6/Annex II (MDR High-Risk), identifying clinical decision support systems as High-Risk.

**Step 3: Risk Assessment (NIST AI RMF)**
Evaluation of 8 primary risks categorized by NIST functions (Govern, Map, Measure, Manage) with Likelihood/Impact scoring.

**Step 4: Risk Heatmap & Mitigation Analysis**
Visualization of pre- and post-mitigation risk levels on a 5x5 matrix.

**Step 5: Vendor Governance Scorecard**
Quantitative assessment of FoundationHealth Inc. across transparency, security, and contractual protections.

**Step 6: Model Performance (Model Card)**
Evaluation of "Top-3 Diagnostic Accuracy" across demographics, including fairness checks for age and condition types.

**Step 7: Monitoring & Incident Response**
Strategic design of real-time monitoring coverage and incident severity classifications (S1-S4).

**Step 8: Executive Governance Dashboard**
Synthesis of overall readiness scores (65-90%) into a board-ready dashboard.

---

## Technical Implementation

### Repository Structure

```
ai-governance-assessment/
├── data/                          ← Input datasets
│   ├── system_spec.json           ← ClinicalCompanion specification
│   ├── training_data_summary.csv  ← Training data sources
│   ├── performance_metrics.csv    ← Model performance by subgroup
│   ├── risk_register.csv          ← Risk register (NIST AI RMF)
│   ├── vendor_assessment.csv      ← Vendor criteria + scores
│   ├── vendor_profile.json        ← Vendor company profile
│   ├── eu_ai_act_requirements.csv ← EU AI Act requirements
│   ├── monitoring_kpis.csv        ← Monitoring KPI definitions
│   ├── incident_types.csv         ← Incident taxonomy
│   └── severity_levels.csv        ← Incident severity definitions
├── results/                       ← Assessment Visualization Results
│   ├── executive_dashboard.png
│   ├── model_card_performance.png
│   ├── monitoring_dashboard.png
│   ├── risk_heatmap.png
│   ├── risk_mitigation_comparison.png
│   └── vendor_evaluation_chart.png
├── governance_assessment.ipynb    ← Data-driven assessment code
└── governance_workbook.xlsx       ← Strategic Governance Deliverable
```

### Visualizations

The `results/` folder contains generated PNG artifacts of the analysis, including:
- **Risk Heatmap** (NIST AI RMF)
- **Risk Mitigation Effectiveness**
- **Vendor Governance Radar Chart**
- **Disaggregated Performance Bar Chart**
- **4-Panel Monitoring Dashboard**
- **Executive Readiness Gauge**

---

## Final Readiness Summary

ClinicalCompanion is currently assessed at an overall governance readiness of **79.2%**. While core technical documentation and safety monitoring are strong (70-90%), compliance with specific Article 10 dataset representativeness requirements is currently at **65%**, requiring further clinical data collection from underrepresented subgroups before the final launch.

---

MedAssist AI Clinical Assessment Group
