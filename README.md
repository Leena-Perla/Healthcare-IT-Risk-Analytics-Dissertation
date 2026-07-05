# Healthcare IT Project Risk Analytics — MSc Dissertation

A business analytics approach to identifying and categorising socio-technical risks in Healthcare IT (HIT) projects, using qualitative content analysis and an interactive Power BI dashboard.

## Overview

Healthcare IT projects (EHRs, HIS, CDSS) frequently fail, run over budget, or get delayed — not usually due to technical errors, but due to socio-technical issues: governance gaps, workflow misalignment, and human factors. This project analyzed 392 risks extracted from 40+ published academic and industry sources (2000–2025), coded them into a structured framework, and built an interactive Power BI dashboard for cross-context risk analysis.

## Method

- Qualitative content analysis of healthcare IT project literature
- Risks coded across 9 dimensions: category, region, hospital type, project type, lifecycle phase, infrastructure level, investment level, and risk theme
- Dataset analyzed and visualized in Power BI with interactive filtering, tree maps, and cross-tabulation

## Key Findings

- Governance risks were the most common category (128 of 392 risks), followed by human factors (64) and workflow/process misalignment (57) — technical failures were comparatively less frequent (52)
- Governance and workflow risks were persistent across nearly every lifecycle phase, hospital type, and region — not isolated incidents
- Risk patterns differed by context: OECD countries showed more governance-related risk, while LMICs (e.g. Saudi Arabia, Iran) showed more technical/infrastructure risk
- Teaching/tertiary hospitals accounted for the largest share of documented risks (252 of 392), reflecting their prevalence in large, high-investment projects

## Files

- `data/Data.xlsx` — the coded risk dataset (392 risks across 9 classification dimensions)
- `powerbi/dissertation.pbix` — the interactive Power BI dashboard (open in Power BI Desktop to explore filters, tree maps, and cross-tabulations)

## Tools

Power BI (DAX measures, interactive filtering, tree maps, geographic mapping) · Qualitative Content Analysis · Excel

---

MSc Business Analytics and Management Science, University of Southampton, 2024-2025
