# ECG reliability screening with fixed calibration

![Conceptual scientific cover](https://raw.githubusercontent.com/terry0809000/earlybird-ecg-reliability/main/assets/project-cover.png)

Before asking a model to read an ECG, I want to understand what it is actually hearing. This project explores reliability screening when the waveform is perturbed, with calibration fixed before the held-out evaluation.

The code keeps patient grouping, frozen fitting and staged test acquisition explicit. Injected noise gives us a controlled question; it does not give us clinician-certified signal-quality labels. This source-only release requires separately acquired waveforms and the original authorized development manifests.

**Research direction:** AI for Health

## Explore the code

[Open the repository](https://github.com/terry0809000/earlybird-ecg-reliability) · [README](https://github.com/terry0809000/earlybird-ecg-reliability/blob/main/README.md) · [Pipeline and commands](https://github.com/terry0809000/earlybird-ecg-reliability/blob/main/PIPELINE.md) · [Data access](https://github.com/terry0809000/earlybird-ecg-reliability/blob/main/DATA_ACCESS.md)

## Methods and inputs

Fixed calibration, patient-held-out perturbation screening and staged ECG test acquisition.

PTB-XL and NSTDB source releases; acquire source waveforms and any noise inputs separately.

## Scope

Injected perturbation labels are not clinician-certified signal quality; source-only reproduction requires separately acquired original manifests.

Existing source was organized for publication; scientific experiments and tests were not rerun. Cover art is conceptual and does not depict measured results.

[Return to the portfolio](../README.md)
