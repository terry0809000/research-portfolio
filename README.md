<p align="center"><img src="assets/header.svg" width="100%" alt="For the people behind the data — Tianyi Yu" /></p>

[Meet me](https://github.com/terry0809000) · [Google Scholar](https://scholar.google.com/citations?user=m8F5KU8AAAAJ) · [ORCID](https://orcid.org/0009-0009-0311-4015)

A clinical note holds someone's story. An image can carry a clue that is easy to miss. A risk score may shape what happens next.

That is what draws me to AI for health. I want to understand what these tools can learn, where they fall short, and what it would take to make them useful to the people who depend on them.

I'm **Tianyi Yu**. I work across clinical language, biomedical imaging and prediction modelling, with a particular interest in trust: does a promising result survive a new hospital, a different population, or the messiness of everyday care?

This is where I share the code behind those questions. Pick a project, look under the hood, and try it with your own questions. I'd love to hear what you find.

## The questions that keep me curious

| Where I work | What I want to understand | A place to start |
|:--|:--|:--|
| **Clinical NLP** | How much of a clinical story can a model understand—and what does it miss? | [Clinical text & social determinants](pipelines/MIMIC_SBDH.md) · [Trial inference](pipelines/clinical-trial-inference-joint-audit.md) |
| **Computer Vision & Biomedical Imaging** | Can we find useful signals in images and recognise when a model is unsure? | [Skin-lesion referral](pipelines/ham10000-trustworthy-skin-ai.md) |
| **Trustworthy AI** | When should we trust a prediction, question it, or ask for another opinion? | [Beyond Macro-F1](pipelines/beyond-macro-f1-pubmed-rct-public.md) · [TRACE-Fib](pipelines/trace-fib-pipeline.md) |
| **Prediction Modelling** | Will a model still help when the hospital, population or timing changes? | [ARDS / AHRF](pipelines/ards-ahrf-ehr-temporal-validation.md) · [Dynamic AKI](pipelines/aki-dynamic-prediction-deployment-gated.md) |
| **Health Informatics** | What do the ways we collect and record data reveal about care? | [ICU measurement patterns](pipelines/icu-measurement-aware-prediction.md) · [Glucose-testing gaps](pipelines/brfss-glucose-testing-access.md) |
| **AI for Health** | Where can computation help us see a health problem more clearly? | [Sleep signals](pipelines/sleepingedf.md) · [Respiratory surveillance](pipelines/bmc-dm-prediction-one-week.md) |

## Explore the projects

Follow a question that interests you. Each project opens into its own code, methods and guide to getting started.

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
| [Healthcare access and glucose-testing gaps](pipelines/brfss-glucose-testing-access.md) | Health Informatics | BRFSS 2024–2025 |
| [Preprocessing sensitivity of glomerular BEX3 prioritisation](pipelines/dkd-bex3-preprocessing.md) | AI for Health | GEO · kidney expression data |
| [Temporal liver elastography triage](pipelines/liver-elastography-temporal-triage.md) | Prediction Modelling | Public-use NHANES |
| [Clinical trial inference: reference and answer-mapping sensitivity](pipelines/clinical-trial-inference-joint-audit.md) | Clinical NLP | Trial reports · language models |
| [Availability-aware source selection for clinical NLP](pipelines/availability-aware-clinical-nlp.md) | Clinical NLP | E3C · source reports · authorized inputs |
| [Measurement-aware retrospective ICU prediction](pipelines/icu-measurement-aware-prediction.md) | Prediction Modelling | Credentialed MIMIC-IV / eICU |
| [AMI-CS dynamic risk modelling](pipelines/ami-cs-dynamic-risk-modeling.md) | Prediction Modelling | Credentialed MIMIC-IV / eICU |
| [Sepsis-to-shock temporal prediction](pipelines/sepsis-shock-ai-medicine-v9.md) | Prediction Modelling | Credentialed MIMIC-IV / eICU |
| [Social and behavioural determinants from clinical text](pipelines/MIMIC_SBDH.md) | Clinical NLP | Authorized MIMIC-III text / MIMIC-SBDH annotations |

## Open the code. Ask another question.

The most interesting part of sharing a project is seeing what someone else notices. If you spot a fragile assumption, have a better approach, or want to explore a related problem, [open an issue in the relevant repository](https://github.com/terry0809000?tab=repositories). Thoughtful questions are welcome.

To run a project, start with its README and data-access guide. Each repository explains its environment, inputs and analysis steps; some clinical datasets require authorized access.

<details>
<summary>A few practical notes before you run anything</summary>

- Use the project's own versioned dependencies, configuration and execution instructions.
- Clinical records and patient-level outputs stay in the environment where you are authorized to use them.
- Some workflows need separately acquired data or saved artifacts. Source availability alone does not establish a full reproduction.
- This portfolio update did not retrain or independently rerun every model. Synthetic checks and retrospective results have their own limits, described in the individual projects.
- Manuscripts and submission materials stay outside the software repositories. Original source licenses and data conditions apply.

For a machine-readable project list, see [projects.json](projects.json).

</details>
