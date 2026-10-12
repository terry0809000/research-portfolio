[Home](../README.md) · [About](../sections/about.md) · [Research](../sections/research.md) · [Projects](../sections/projects.md) · [Approach](../sections/approach.md) · [Connect](../sections/connect.md)

# Selective review and total sleep time estimation

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/sleep-duration-selective-review/main/assets/project-cover.png)

A night of sleep contains thousands of small decisions. I wanted to explore where a limited review budget might matter most for estimating total sleep time, instead of treating every epoch as equally uncertain.

The code compares selective-review policies using frozen sleep predictions and archived expert annotations, then examines error accounting and policy refitting. The study is exploratory and retrospective: archived labels simulate review, and the stability analyses do not represent new clinicians or prospective clinical validation.

**Research direction:** AI for Health

## Explore the code

[Open the repository](https://github.com/terry0809000/sleep-duration-selective-review) · [README](https://github.com/terry0809000/sleep-duration-selective-review/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/sleep-duration-selective-review/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/sleep-duration-selective-review/blob/main/DATA_ACCESS.md)

## Methods and inputs

Frozen sleep predictions, review-policy calibration, reviewer rotation and fixed-fold refitting stability.

Obtain source PSG/hypnograms and any licensed model weights separately; epoch-level evidence is excluded.

## Scope

Archived expert labels simulate review; the exploratory retrospective study does not establish prospective clinical utility.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
