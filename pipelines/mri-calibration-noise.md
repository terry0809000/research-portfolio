# MRI calibration-noise analysis

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/mri-calibration-noise/main/assets/project-cover.png)

MRI reconstruction depends on calibration as well as the measured signal. I wanted to explore how recalibrating sensitivity maps carries added noise through a reconstruction, and what changes when those maps are held fixed.

This source release includes the primary probes, saved configurations, descriptive replication and bounded numerical diagnostics. The experiments model independent added noise around already noisy measured data. They are preliminary mechanism studies, not estimates of native scanner covariance or evidence of clinical superiority.

**Research direction:** Computer Vision & Biomedical Imaging

## Explore the code

[Open the repository](https://github.com/terry0809000/mri-calibration-noise) · [README](https://github.com/terry0809000/mri-calibration-noise/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/mri-calibration-noise/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/mri-calibration-noise/blob/main/DATA_ACCESS.md)

## Methods and inputs

Multicoil calibration-noise probes, descriptive replication and finite-difference diagnostics.

Public source MRI releases and fixed development/evaluation splits, as specified in the original code.

## Scope

Added identity-covariance noise around noisy measured data does not estimate native scanner covariance or establish clinical generality.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
