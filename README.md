<p align="center"><img src="assets/header.svg" width="100%" alt="From question to pipeline — Tianyi Yu's research software portfolio" /></p>

[Profile](https://github.com/terry0809000) · [Google Scholar](https://scholar.google.com/citations?user=m8F5KU8AAAAJ) · [ORCID](https://orcid.org/0009-0009-0311-4015)

A curated map of my research software, organized by scientific question. Each entry links to a pipeline and explains its data requirements and interpretation boundary. This is a software portfolio, not a publication list.

## Research directions

| Direction | Representative pipeline |
|:--|:--|
| **Clinical NLP** | [Beyond Macro-F1](https://github.com/terry0809000/beyond-macro-f1-pubmed-rct-public) · [Cross-corpus abstract classification](pipelines/biomedical-abstract-sentence-classification.md) |
| **Computer Vision & Biomedical Imaging** | [Selective skin-lesion referral](https://github.com/terry0809000/ham10000-trustworthy-skin-ai) |
| **Trustworthy AI** | [Calibration and consistency](pipelines/beyond-macro-f1-pubmed-rct-public.md) · [Representation sensitivity](pipelines/trace-fib-pipeline.md) |
| **Prediction Modelling** | [ARDS / AHRF](pipelines/ards-ahrf-ehr-temporal-validation.md) · [Temporal screening](pipelines/nhanes-temporal-diabetes-screening.md) |
| **Health Informatics** | [Dynamic AKI prediction](pipelines/aki-dynamic-prediction-deployment-gated.md) · [SAFE-LABS](pipelines/safelabs-icu-lab-deferral.md) |
| **AI for Health** | [Respiratory surveillance](pipelines/bmc-dm-prediction-one-week.md) · [Sleep staging](pipelines/sleepingedf.md) |

## Pipeline index

22 published research pipelines, each with its own source repository.

| Pipeline | Research area | Inputs / execution context |
|:--|:--|:--|
| [TRACE-Fib](pipelines/trace-fib-pipeline.md) | Computational biology | CPU · public deposit |
| [Beyond Macro-F1](pipelines/beyond-macro-f1-pubmed-rct-public.md) | Biomedical NLP | Public code + versioned evidence |
| [Selective skin-lesion referral](pipelines/ham10000-trustworthy-skin-ai.md) | Medical imaging | Python · acquire source images |
| [ARDS / AHRF temporal validation](pipelines/ards-ahrf-ehr-temporal-validation.md) | Clinical prediction | Credentialed MIMIC-IV / eICU |
| [Reading dynamics with ZuCo 2.0](pipelines/zuco2-scientific-ml-pipeline.md) | Cognitive data science | Python package · acquire ZuCo |
| [Respiratory surveillance](pipelines/bmc-dm-prediction-one-week.md) | Public health | CPU · public aggregate surveillance |
| [Temporal screening evaluation](pipelines/nhanes-temporal-diabetes-screening.md) | Clinical prediction | Python · public-use NHANES |
| [Extubation transportability](pipelines/copd-asthma-extubation-transportability.md) | Clinical prediction | Credentialed MIMIC-IV / eICU |
| [Dynamic AKI prediction](pipelines/aki-dynamic-prediction-deployment-gated.md) | Clinical prediction | Credentialed clinical data |
| [Cross-corpus abstract classification](pipelines/biomedical-abstract-sentence-classification.md) | Biomedical NLP | CPU · public text corpora |
| [Sleep-EDF staging](pipelines/sleepingedf.md) | Physiological signals | Acquire Sleep-EDF |
| [Rationale reliability audit](pipelines/hatespeechcheck.md) | Responsible NLP | Python · acquire benchmark data |
| [SAFE-LABS](pipelines/safelabs-icu-lab-deferral.md) | Research methods | Synthetic validation / protocol |
| [Healthcare access and glucose-testing gaps](pipelines/brfss-glucose-testing-access.md) | Health Informatics | Public-use BRFSS 2024 and 2025; acquire upstream source files locally. |
| [Preprocessing sensitivity of glomerular BEX3 prioritisation](pipelines/dkd-bex3-preprocessing.md) | AI for Health | Public GEO and annotated kidney expression sources; obtain original inputs from their providers. |
| [Temporal liver elastography triage](pipelines/liver-elastography-temporal-triage.md) | Prediction Modelling | Public-use NHANES; cohort extraction and availability rules are in source code. |
| [Clinical trial inference: reference and answer-mapping sensitivity](pipelines/clinical-trial-inference-joint-audit.md) | Clinical NLP | Obtain source trial reports and model checkpoints using original acquisition scripts; third-party texts and model weights excluded. |
| [Availability-aware source selection for clinical NLP](pipelines/availability-aware-clinical-nlp.md) | Clinical NLP | Original source reports, model checkpoints, E3C and authorized laboratory inputs are obtained separately. |
| [Measurement-aware retrospective ICU prediction](pipelines/icu-measurement-aware-prediction.md) | Prediction Modelling | Credentialed MIMIC-IV 3.1 and eICU 2.0. Set ICU_RAW_ROOT and ICU_EXTRACT_ROOT locally; generated rows and models remain private. |
| [AMI-CS dynamic risk modelling](pipelines/ami-cs-dynamic-risk-modeling.md) | Prediction Modelling | Credentialed MIMIC-IV / eICU |
| [Sepsis-to-shock temporal prediction](pipelines/sepsis-shock-ai-medicine-v9.md) | Prediction Modelling | Credentialed MIMIC-IV / eICU |
| [Social and behavioural determinants from clinical text](pipelines/MIMIC_SBDH.md) | Clinical NLP | Authorized MIMIC-III text / MIMIC-SBDH annotations |

## Reproduction, stated precisely

- Follow each pipeline's pinned environment and data-access instructions. Public code does not imply unrestricted source data.
- A synthetic test verifies software behavior; it is not an empirical replication or clinical validation.
- The new TRACE-Fib wrapper separates tests, frozen-result verification and full analysis. Other repositories retain their own entry points; a catalogue listing is not a claim that all models were retrained during this portfolio refresh.
- Negative findings and scope limits are part of the result. Repository availability does not imply journal acceptance.

## Repository policy

Project repositories contain analysis code, configurations, dependency specifications, tests, reproduction instructions and permitted evidence. Manuscript text, title pages, cover letters and submission bundles belong outside the software repositories. Credentialed clinical inputs, patient-level derivatives and private administrative material must remain in their authorized environments.

The catalogue is also available as [structured JSON](projects.json). Source history and source-specific licenses remain with each project.
