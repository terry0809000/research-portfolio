[Home](../README.md) · [About](../sections/about.md) · [Research](../sections/research.md) · [Projects](../sections/projects.md) · [Approach](../sections/approach.md) · [Connect](../sections/connect.md)

# ECG models under label and sampling budgets

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/ecg-label-budget-model-comparison/main/assets/project-cover.png)

More labels and a higher sampling rate both cost something. I compare ECG learning pipelines under those constraints, keeping patient separation, training variability and computational cost in the same conversation.

The five diagnostic labels are multi-hot. Training folds 1–8, validation fold 9 and test fold 10 stay separate; validation-label budgets are additional to the training budgets. This project is distinct from the EarlyBird perturbation-screening pipeline.

**Research direction:** AI for Health

**Also:** Prediction Modelling

## The question

How do ECG model comparisons change with training-label budgets, sampling rates and computational cost?

## Methods and inputs

PTB-XL patient-disjoint folds, shared deterministic subsets, multi-seed model comparison and paired patient bootstrap.

Acquire PTB-XL v1.0.3 directly from PhysioNet under its terms.

[Open the source and pipeline →](https://github.com/terry0809000/ecg-label-budget-model-comparison)

## Evidence boundary

A controlled retrospective multi-label benchmark; hardware-specific timing and model comparisons do not establish clinical readiness.

Existing study source was organized for this portfolio; scientific experiments and tests were not rerun. The AI-generated cover is conceptual raster artwork.

[Return to this direction](../directions/ai-for-health.md)
