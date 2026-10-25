# HVAC-XForecast Reliability Control

Reproducibility materials for **Beyond Forecast Accuracy: Cross-Site Calibration and Empirical Risk Control for Cooling-Load Forecasting**.

## Public release scope

This public repository documents the 168-hour context to 24-hour horizon cooling-load forecasting task, cohort and site-holdout membership, evaluation protocols, delayed recalibration, sensor-stress settings, and empirical risk-budget evaluation.

Current public contents include:

- `cohort_manifest/` — site-level cohort and eligibility documentation
- `splits/` — site-holdout membership and split protocol
- `configs/` — forecast, reliability, stress, recalibration, and risk-budget settings
- `supplementary_tables/` — selected machine-readable result tables
- `analysis/` — public analysis-scope documentation
- `environment/` — environment-release notes
- `REPOSITORY_RELEASE_MANIFEST.md` — inclusion and exclusion boundary

The current release supports verification of cohort definitions, protocol settings, selected result tables, and empirical risk-budget endpoints. It is not described as a complete end-to-end retraining package.

## Data and third-party models

Raw Building Data Genome Project 2 data are not redistributed. Users should obtain them from the official source. Third-party pretrained model weights are also not redistributed and should be obtained from their official providers.

## Forecasting task

- Historical context: 168 hours
- Forecast horizon: 24 hours
- Evaluation settings: chronological in-domain, building-held-out, and exact site-held-out

## Citation

A formal citation will be added after publication metadata become available.

## Contact

Chun-Jan Tseng  
Department of Data Science, Soochow University  
Email: cjtseng@scu.edu.tw

## Licensing

No repository-wide software license has been selected yet. Third-party data and model artifacts remain subject to their original licenses.
