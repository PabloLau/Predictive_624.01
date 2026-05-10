# Healthcare Claims Predictive Analytics Framework

## Overview
This project explores how predictive analytics and behavioral machine learning can complement traditional rules-based payment integrity systems within healthcare claims operations.
Using CMS synthetic Medicare claims data (SynPUF), the framework evaluates whether machine learning models can identify suspicious claim patterns more intelligently than static rules engines alone.
---

## Objectives
The project focuses on:
- Claims audit prioritization
- Behavioral anomaly detection
- High-cost claim contextualization
- Near-duplicate billing detection
- Frequency/utilization pattern analysis
- Operational threshold optimization
- Human validation governance workflows
- Explainability and audit transparency
---

## Key Concepts
Traditional claims systems often rely on static rules such as:
- High-dollar thresholds
- Duplicate claim logic
- Frequency edits
- Modifier edits
- Geographic edits

This framework explores how predictive models can:
- Reduce unnecessary audits
- Improve targeting precision
- Detect subtle behavioral manipulation
- Prioritize claims review queues
- Support operational governance

## Features Engineered
Examples include:
- Provider payment behavior
- Procedure rarity scores
- Geographic peer comparison
- Provider variability metrics
- Utilization patterns
- Member risk scoring
- Near-duplicate behavioral detection
- Temporal utilization trends

---

## Machine Learning Techniques
- Random Forest
- Threshold optimization
- ROC/AUC analysis
- Confusion matrices
- Feature importance explainability
- Human validation sampling

## Key Findings
The analysis demonstrated that:
- Many traditionally flagged claims become operationally explainable when contextual factors are introduced.
- Behavioral models can identify suspicious patterns that static rules may miss.
- Operational thresholds can balance audit workload against suspicious-claim capture rates.
- AI is most effective when used alongside human governance and traditional rules engines.

## Governance
This project includes:
- Explainability outputs
- Human validation sampling
- Auditor feedback workflows
- Threshold governance concepts

## Disclaimer
This project uses CMS synthetic Medicare claims data (SynPUF) for educational and research purposes only.
No PHI, proprietary payer data, or production systems are included.

## Future Enhancements
Planned enhancements include:
- Gradient boosting models
- Ensemble modeling
- SHAP explainability
- Specialty-specific segmentation
- Time-series provider behavior analysis
- Real-time scoring architectures
