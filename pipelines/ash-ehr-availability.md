[Home](../README.md) · [About](../sections/about.md) · [Research](../sections/research.md) · [Projects](../sections/projects.md) · [Approach](../sections/approach.md) · [Connect](../sections/connect.md)

# Availability-aware EHR modelling

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/ash-ehr-availability/main/assets/project-cover.png)

A measurement in a record is not always a measurement a model could have seen at the time. I built this project around that gap: replaying clinical information as it becomes available, and keeping the rules fixed before evaluating predictions.

The saved code compares availability policies through frozen EHR extraction and modelling workflows. Patient clustering, unit mappings and review receipts stay explicit. Credentialed inputs and original review artifacts must be obtained separately; this repository contains the scientific source, not patient records or fitted models.

**Research direction:** Health Informatics

## Explore the code

[Open the repository](https://github.com/terry0809000/ash-ehr-availability) · [README](https://github.com/terry0809000/ash-ehr-availability/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/ash-ehr-availability/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/ash-ehr-availability/blob/main/DATA_ACCESS.md)

## Methods and inputs

Availability-aware EHR replay, frozen extraction and patient-clustered policy comparisons.

Credentialed MIMIC-IV 3.1 and eICU 2.0. Patient rows, labels, predictions and models remain private.

## Scope

Credentialed inputs and genuine original review/freeze artifacts are required separately; clinical deployment is not established.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
