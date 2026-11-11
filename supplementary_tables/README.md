# Machine-readable result tables — scope notice

This directory contains selected tables from the **broader HVAC-XForecast study**, including site-held point metrics, site-held interval reliability, a representative PatchTST delayed-recalibration experiment, and historical empirical risk-budget retention.

Compact metric names:

- Cov90: empirical nominal 90% interval coverage
- CovErr90: mean building-level absolute deviation from nominal 90% coverage
- PeakCov90: peak-conditional nominal 90% interval coverage

**Important distinction:** the current IEEE Access submission candidate, *Beyond Forecast Accuracy: Reliability, Calibration, and Forecast Acceptance under Cross-Building Distribution Shift*, performs a specific nine-site common-final-support audit of a frozen LightGBM forecast, original source interval misses, delayed local probability maps, and acceptance decisions. Earlier machine-readable tables here must **not** be assumed to have the same origin-horizon support, event definitions, mapping strategies, or policy denominators.

For current-paper quantitative claims, use the exact manuscript and Supplementary Material tables unless a public file is explicitly version-matched to the frozen E2 evaluation. Raw BDG2 observations and third-party weights are not redistributed; complete end-to-end replay is not represented as available here.
