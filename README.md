<p align="center"><img src="assets/header.svg" width="100%" alt="From question to pipeline — Tianyi Yu's research software portfolio" /></p>

[Profile](https://github.com/terry0809000) · [Google Scholar](https://scholar.google.com/citations?user=m8F5KU8AAAAJ) · [ORCID](https://orcid.org/0009-0009-0311-4015)

A curated map of my research software, organized by scientific question. Each entry links to a pipeline and explains its data requirements and interpretation boundary. This is a software portfolio, not a publication list.

## Start here

| Interest | Suggested entry |
|:--|:--|
| Reproduce a bounded public-data analysis | [TRACE-Fib](https://github.com/terry0809000/trace-fib-pipeline) |
| Inspect calibration beyond headline accuracy | [Beyond Macro-F1](https://github.com/terry0809000/beyond-macro-f1-pubmed-rct-public) |
| Explore an installable research package | [ZuCo 2.0](https://github.com/terry0809000/zuco2-scientific-ml-pipeline) |
| Study cross-database clinical validation | [ARDS / AHRF](https://github.com/terry0809000/ards-ahrf-ehr-temporal-validation) |

## Pipeline index

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

## Reproduction, stated precisely

- Follow each pipeline's pinned environment and data-access instructions. Public code does not imply unrestricted source data.
- A synthetic test verifies software behavior; it is not an empirical replication or clinical validation.
- The new TRACE-Fib wrapper separates tests, frozen-result verification and full analysis. Other repositories retain their own entry points; a catalogue listing is not a claim that all models were retrained during this portfolio refresh.
- Negative findings and scope limits are part of the result. Repository availability does not imply journal acceptance.

## Repository policy

Project repositories contain analysis code, configurations, dependency specifications, tests, reproduction instructions and permitted evidence. Manuscript text, title pages, cover letters and submission bundles belong outside the software repositories. Credentialed clinical inputs, patient-level derivatives and private administrative material must remain in their authorized environments.

The catalogue is also available as [structured JSON](projects.json). Source history and source-specific licenses remain with each project.
