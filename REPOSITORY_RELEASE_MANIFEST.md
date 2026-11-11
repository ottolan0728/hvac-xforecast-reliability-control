# HVAC-XForecast public repository release manifest

Updated for the IEEE Access submission candidate **Beyond Forecast Accuracy: Reliability, Calibration, and Forecast Acceptance under Cross-Building Distribution Shift** (November 2026).

## Included in the current public repository

- Site-level cohort manifest and site-held-out membership documentation
- Original split protocol
- Archived forecasting and reliability-evaluation configurations
- Stress-test and delayed-recalibration configuration descriptions
- Empirical risk-budget configuration descriptions
- Selected machine-readable result tables from the broader HVAC-XForecast study
- Analysis scope and environment-release documentation

## Not established by this public release

- Complete end-to-end replication of frozen model training or the current nine-site final-support calibration/acceptance evaluation
- A fully pinned runtime with all historical dependencies
- Public availability of every source-fold residual, frozen issued prediction, source threshold helper, model checkpoint, or complete historical figure-generation script
- Direct equivalence of every earlier published table to the current fixed-event paper's denominators and policies
- Physical chiller operation, monetary energy savings, regret, or a target-site risk guarantee

## Excluded

- Raw Building Data Genome Project 2 (BDG2) observations
- Third-party pretrained model weights
- Credentials, API keys, private data, or unavailable upstream artifacts
- Unverified software-version claims

## Verification boundary

The **current paper and its Supplementary Material** define the nine-site fixed-event analysis. This repository presently supports inspection of archived cohort/split settings and selected study outputs, but should not be cited as a complete independent code-level replay of the paper. Match any reused table to its provenance, study phase, and evaluation support before making quantitative claims.

No repository-wide software license has been granted; third-party materials remain subject to original terms. A versioned release tag and any expanded reproducibility files should be added only after their exact contents and rights have been checked.
