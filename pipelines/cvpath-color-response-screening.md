# Color-response sensitivity for pathology error screening

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/cvpath-color-response-screening/main/assets/project-cover.png)

A pathology classifier can be confident and still be wrong. I wanted to explore whether its response to controlled color perturbations reveals something that the original confidence score misses.

This project preserves the PathMNIST224 source training, fixed-classifier screening methods and source-to-target evaluation sequence. Scorer fitting and thresholds are frozen before target access. The derivative dataset lacks patient and slide identifiers, so patch-level checks do not establish patient independence or clinical effectiveness.

**Research direction:** Computer Vision & Biomedical Imaging

## Explore the code

[Open the repository](https://github.com/terry0809000/cvpath-color-response-screening) · [README](https://github.com/terry0809000/cvpath-color-response-screening/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/cvpath-color-response-screening/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/cvpath-color-response-screening/blob/main/DATA_ACCESS.md)

## Methods and inputs

Fixed PathMNIST224 classifiers, color-response screening scores and frozen source-to-target evaluation.

PathMNIST224, CC BY 4.0; obtain from the documented Zenodo release. Training needs CUDA-capable hardware.

## Scope

Patch-level derivative data lack patient/slide identifiers; source and external partitions do not establish wholly unseen institutions.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
