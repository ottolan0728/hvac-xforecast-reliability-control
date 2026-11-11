# HVAC-XForecast Reliability Control

Research release documentation associated with the IEEE Access submission candidate:

**Beyond Forecast Accuracy: Reliability, Calibration, and Forecast Acceptance under Cross-Building Distribution Shift**

Authors: Chun-Jan Tseng, Yi-Kai Su, and Ming-Han Chang. Corresponding author: Yi-Kai Su.

**Status:** manuscript under preparation / pre-submission audit (November 2026). This repository is not a record of journal acceptance or publication.

## Research focus

The current manuscript examines whether improving the calibration of the probability that a *fixed source-derived prediction interval* will miss an observed cooling load improves forecast-acceptance decisions at unseen building sites. It separates four empirical endpoints: probability calibration, matched-retention ranking, observed accepted-set interval failure, and retained service.

The audited experiment uses a frozen Light Gradient Boosting Machine (LightGBM) target forecaster, a 168-hour input context and 24-hour horizon, an original source-derived nominal 90% interval, frozen issued-model disagreement, and chronologically matured target-site labels. The primary final-support comparison covers nine site-held-out domains. The interval-failure event is unchanged by subsequent probability mapping.

The manuscript describes three **procedural replay algorithms**: Frozen Source-Interval Replay, Issuance-Time Failure-Risk Replay, and Fixed-Policy Acceptance and Outcome Audit. These organize existing frozen computations and decision evaluations; they are not claims of a new conformal theorem, target-domain coverage guarantee, or physical chiller-control deployment.

## Public release scope

This repository currently contains documentation and selected machine-readable materials developed across the HVAC-XForecast study, including:

- `cohort_manifest/`: site-level cohort and eligibility documentation
- `splits/`: original site-holdout membership and split protocols
- `configs/`: archived forecasting, reliability, stress, recalibration, and risk-budget settings
- `supplementary_tables/`: selected machine-readable outcomes from the broader study (see the directory README for scope)
- `analysis/`: analysis-scope documentation
- `environment/`: environment-release notes
- `REPOSITORY_RELEASE_MANIFEST.md`: inclusion and exclusion boundary

**Version boundary:** some public figures, configurations, and result tables document the broader historical forecasting study rather than the current nine-site fixed-event calibration/acceptance evaluation. Unless a file is explicitly identified as part of that frozen final-support evaluation, it must not be used as evidence for its treatment contrasts. Consult the current manuscript and Supplementary Material for the exact cohorts, denominators, definitions, algorithms, and reported results.

The public repository **does not currently provide** a complete end-to-end retraining/re-execution environment, all archived upstream policy helpers, raw BDG2 observations, or third-party pretrained model weights. No independent reconstruction of every manuscript result from this repository alone is claimed.

## Data and third-party models

The source data are from the Building Data Genome Project 2 (BDG2). Obtain them from the original provider under its access and use conditions; the raw dataset is not redistributed here. Third-party model weights remain subject to their providers' licenses and are not redistributed.

## Reproducibility and citation

The current manuscript and Supplementary Material provide formal problem definitions, procedural pseudocode, and the frozen experiment's evaluation boundaries. Before relying on any public table as a machine-readable source for the final nine-site audit, verify its support and version against the manuscript.

A journal citation and immutable release tag will be added when the submission/release package is finalized. Until then, reference this repository by its URL and explicitly state its limited scope.

## Contact

Manuscript correspondence: **Yi-Kai Su** (ndmcc10003@gmail.com).  
Repository/project contact: **Chun-Jan Tseng**, Department of Data Science, Soochow University (cjtseng@scu.edu.tw).

## Licensing

No repository-wide software license has been selected. Public visibility does not by itself grant reuse rights. Original BDG2 data, third-party model weights, and externally authored materials retain their separate terms. Any future software license should be selected by the rights holders and must not be interpreted as relicensing third-party assets.
