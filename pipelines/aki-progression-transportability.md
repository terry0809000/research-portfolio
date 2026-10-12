[Home](../README.md) · [About](../sections/about.md) · [Research](../sections/research.md) · [Projects](../sections/projects.md) · [Approach](../sections/approach.md) · [Connect](../sections/connect.md)

# AKI progression: transportability and model updating

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/aki-progression-transportability/main/assets/project-cover.png)

A model carries the history of the patients and care setting it learned from. I want to understand what happens when that history meets a different clinical database, especially when kidney injury can progress quickly.

This project preserves raw-archive cohort construction, tabular and temporal models, external evaluation and updating analyses. It keeps eligibility, extraction scope and calibration separate so that a change in the data is not mistaken for a change in clinical truth. Patient-level artifacts and fitted weights remain private.

**Research direction:** Prediction Modelling

## Explore the code

[Open the repository](https://github.com/terry0809000/aki-progression-transportability) · [README](https://github.com/terry0809000/aki-progression-transportability/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/aki-progression-transportability/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/aki-progression-transportability/blob/main/DATA_ACCESS.md)

## Methods and inputs

AKI raw-archive cohort construction, tabular/temporal models, external evaluation and local calibration/updating.

Credentialed MIMIC-IV 3.1 and eICU 2.0. Original records, individual predictions, original hospital identifiers and fitted weights are excluded.

## Scope

Cross-database differences and extraction scope limit transportability; retrospective updating is not prospective deployment evidence.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
