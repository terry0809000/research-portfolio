# Relative and absolute augmentation gains under observation loss

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/clinical-observation-loss-augmentation/main/assets/project-cover.png)

A relative improvement can sound encouraging while the underlying predictions are getting worse. I built this project to keep both views in sight when clinical observations disappear.

The saved PhysioNet workflows separate source-only fitting from held-out evaluation and compare observation-loss policies under explicit masking contracts. Controlled missingness is an experimental intervention on inputs, not a claim that real hospital outages follow the same mechanism. Data, caches, models and individual predictions remain outside this source release.

**Research direction:** Trustworthy AI

## Explore the code

[Open the repository](https://github.com/terry0809000/clinical-observation-loss-augmentation) · [README](https://github.com/terry0809000/clinical-observation-loss-augmentation/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/clinical-observation-loss-augmentation/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/clinical-observation-loss-augmentation/blob/main/DATA_ACCESS.md)

## Methods and inputs

PhysioNet source-only fitting, explicit observation masking and locked held-out augmentation comparisons.

Public PhysioNet Challenge 2012 and 2019 source inputs; acquire raw files separately and retain the original source splits.

## Scope

Relative gains must be read alongside absolute performance; controlled observation loss does not establish real hospital outage behaviour.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
