# Satellite Telemetry Anomaly Detection & Event-Level Evaluation

**Research project | University of Waterloo · AEL-Lab | 2025–2026**

**Research assistant:** Yan Cui  
**Supervisors:** Prof. Peng Hu and Prof. Yeying Zhu

> **Research portfolio overview.** This is an independent, public-facing summary of my contributions to a collaborative research project. It is **not** the laboratory's official repository and contains no private research source code, internal datasets, or unpublished experimental artifacts.

## Research overview

Reliable evaluation of time-series anomaly detection is challenging when anomalies occur over **intervals rather than isolated observations**. A detector may identify part of an anomalous event, flag the event late, fragment it into several alarms, or produce false positives around the event boundaries. Pointwise metrics do not always reflect these distinctions.

This project investigated anomaly detection and **event-level evaluation** for multivariate satellite telemetry using the **ESA Anomaly Detection Benchmark (ESA-ADB)**. The research focused on how evaluation choices, threshold calibration, and anomaly characteristics affect comparisons between detection methods.

## My research contributions

- **Benchmarking and evaluation:** Developed Python workflows to evaluate anomaly detection methods on satellite telemetry, including comparisons across channels and anomaly patterns.
- **Model comparisons:** Experimented with classical and deep-learning approaches, including Isolation Forest, autoencoder-based methods, and sequence-based detection pipelines.
- **Event-level metrics:** Investigated how temporal overlap, detection delay, fragmented predictions, and false alarms affect anomaly-detection scores and model rankings.
- **Threshold sensitivity:** Studied how detection thresholds and metric design influence evaluation outcomes and the interpretation of model performance.

These points summarize my research responsibilities; they do not imply sole ownership of the overall project or its results.

## Research questions

1. How should a metric reward *timely and sufficiently complete* detection of an anomalous interval?
2. How should it penalize fragmented alerts and detections extending beyond the true event?
3. How robust are model comparisons to different thresholds, anomaly types, and scoring rules?

## Methodological focus

| Area | Focus |
| --- | --- |
| Time-series analysis | Multivariate telemetry, irregular sampling, and event intervals |
| Detection methods | Classical anomaly detectors and neural-network approaches |
| Statistical evaluation | Event overlap, temporal localization, fragmentation, and false alarms |
| Experimental analysis | Model benchmarking, threshold sensitivity, and ranking stability |

## Data and reproducibility

The study uses the publicly documented **ESA-ADB** benchmark. For dataset definitions and public benchmark material, see:

- [ESA-ADB benchmark paper](https://arxiv.org/abs/2406.17826)
- [ESA-ADB dataset record](https://zenodo.org/records/15237121)

This repository contains **documentation only**. It does not claim that the experiments can be reproduced from the contents of this showcase. Original research code and any nonpublic materials remain with the collaborating research team.

## Project context

This work was carried out collaboratively with the AEL-Lab research team. My role centered on model evaluation, benchmarking experiments, and studying event-based metrics for reliable comparison of time-series anomaly detectors.

**Contact:** [Yan Cui — GitHub](https://github.com/Y237cui)
