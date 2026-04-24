# Bank Acquisition Data Migration — AI Intelligence System
### Project APEX: NorthernBank | PrimeBank Acquisition

---

## Business Context

NorthernBank has acquired PrimeBank. This repository documents 
the AI-powered intelligence system built to manage the migration 
of 10 million customers and 7 million accounts from PrimeBank's 
SAP ECC 6.0 platform to NorthernBank's Temenos T24 core banking 
system — one of the most complex data migration programmes in 
European retail banking.

**This project is based on real programme experience from a 
major European bank acquisition led at Deloitte.**

---

## System Architecture
```
SAP ECC Extract → Data Profiling → Risk Scoring Model → 
AI Remediation Agent → Steering Committee Dashboard
```

---

## Notebooks

| # | Notebook | Purpose |
|---|----------|---------|
| 01 | Data Profiling & Quality | Profile 10M customer records, identify blockers |
| 02 | Migration Risk Scoring | ML model predicting migration failures |
| 03 | AI Remediation Agent | Autonomous diagnosis and remediation planning |
| 04 | Steering Committee Dashboard | Executive KPI tracking and RAG reporting |

---

## Key Results

- Risk model AUC >0.85 — identifies failures before migration
- Remediation agent processes thousands of cases automatically
- Regulatory rules engine aligned to AMLD6, FATCA, CRS, OFAC
- Full audit trail of all agent decisions for regulatory review

---

## Technologies

Python · pandas · scikit-learn · Random Forest · 
Gradient Boosting · Matplotlib · Agentic AI (custom)

---

## Domain Coverage

SAP BODS · SAP ECC · Temenos T24 · KYC/AML · 
PEP Screening · Sanctions · AMLD6 · Data Governance
