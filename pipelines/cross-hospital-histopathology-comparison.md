[Home](../README.md) · [About](../sections/about.md) · [Research](../sections/research.md) · [Projects](../sections/projects.md) · [Approach](../sections/approach.md) · [Connect](../sections/connect.md)

# Histopathology models across hospitals

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/cross-hospital-histopathology-comparison/main/assets/project-cover.png)

A model can distinguish tissue patches well and still give probabilities that travel poorly. I compare four pretrained image classifiers across hospitals, keeping discrimination, reliability and the cost of inference visible together.

This is a custom patient-grouped CAMELYON17-WILDS protocol, not a reproduction of the official leaderboard split. Negative and uncertain comparisons remain part of the study; timing describes the measured hardware and excludes image I/O.

**Research direction:** Computer Vision & Biomedical Imaging

**Also:** Trustworthy AI

## The question

How do discrimination, probability reliability and computational cost change across hospitals for four pretrained image models?

## Methods and inputs

Patient-grouped CAMELYON17-WILDS evaluation, source-only model selection, paired uncertainty and model-only timing.

Acquire CAMELYON17-WILDS v1.0 and pretrained checkpoints separately.

[Open the source and pipeline →](https://github.com/terry0809000/cross-hospital-histopathology-comparison)

## Evidence boundary

A fixed source-only comparison of four named ImageNet checkpoints; no universal ranking, equivalence or clinical benefit is established.

Existing study source was organized for this portfolio; scientific experiments and tests were not rerun. The AI-generated cover is conceptual raster artwork.

[Return to this direction](../directions/biomedical-imaging.md)
