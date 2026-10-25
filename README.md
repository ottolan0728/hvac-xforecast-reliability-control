# HVAC-XForecast Reliability Control

Reproducibility materials for:

**Beyond Forecast Accuracy: Cross-Site Calibration and Empirical Risk Control for Cooling-Load Forecasting**

## Scope

This repository supports the reproducibility of a cross-site cooling-load forecasting study using the Building Data Genome Project 2 (BDG2). The study evaluates point forecasting, uncertainty calibration, peak-load reliability, structured context degradation, delayed target recalibration, issuance-time forecast-failure scoring, threshold transportability, and empirical risk-budget retention.

## Forecasting task

- Historical context: 168 hours
- Forecast horizon: 24 hours
- Evaluation settings:
  - chronological in-domain
  - building-held-out
  - exact site-held-out

## Data

The study uses publicly available BDG2 data. Raw BDG2 files are **not redistributed** in this repository. Users should obtain the original dataset from its official source and apply the cohort and split manifests provided here.

## Repository structure

- `configs/` — experiment and evaluation configuration files
- `cohort_manifest/` — cohort membership and eligibility metadata
- `splits/` — deterministic evaluation split definitions
- `analysis/` — analysis and result-generation scripts
- `figures/` — figure-generation sources
- `supplementary_tables/` — machine-readable tables supporting the supplementary material
- `environment/` — environment and dependency specifications

## Reproducibility status

The repository is being prepared to accompany the manuscript submission. Public release contents will be limited to materials that can be redistributed legally and reproducibly.

## Third-party models and data

Large third-party model weights and raw BDG2 data are not redistributed. Model checkpoints should be obtained from their official providers.

## Citation

A formal citation will be added after publication metadata become available.

## Contact

Chun-Jan Tseng  
Department of Data Science, Soochow University  
Email: cjtseng@scu.edu.tw

## License

Repository source code and original documentation will be released under the license included in this repository. Third-party data and model artifacts remain subject to their original licenses.
