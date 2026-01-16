# NIL — Tabular Risk / Churn

**Live docs:** https://www.neuromorphicinference.com/demos/tabular-risk  
**Evidence index:** https://www.neuromorphicinference.com/evidence  

## Goal
A production-style tabular scoring system: training + scoring + explainability + drift awareness.

## What it will include
- Train/evaluate a tabular model (AUC/F1 + calibration)
- Batch scoring (upload CSV → outputs)
- Explainability (top drivers, per-prediction rationale)
- Data quality checks (schema, missingness, ranges)
- Drift indicators + “alert simulation” panel

## Intended audiences
- Data Scientist (production)
- Applied ML Engineer
- ML Platform / MLOps (operability + monitoring hooks)
- Data Analyst (scoring + reporting + SQL integration later)

## Status
Planned → in progress

## Roadmap
1) Baseline model + evaluation report
2) Scoring pipeline + explainability
3) Data quality + drift panel + CI checks + tags
