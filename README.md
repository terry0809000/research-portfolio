<p align="center"><img src="assets/ai-for-health-scientific-cover.png" width="100%" alt="For the people behind the data — Tianyi Yu" /></p>

[Visit my website](https://terry0809000.github.io/) · [Meet me](https://github.com/terry0809000) · [Google Scholar](https://scholar.google.com/citations?user=m8F5KU8AAAAJ) · [ORCID](https://orcid.org/0009-0009-0311-4015)

A clinical note holds someone's story. An image can carry a clue that is easy to miss. A risk score may shape what happens next.

That is what draws me to AI for health. I want to understand what these tools can learn, where they fall short, and what it would take to make them useful to the people who depend on them.

I'm **Tianyi Yu**. I work across clinical language, biomedical imaging and prediction modelling, with a particular interest in trust: does a promising result survive a new hospital, a different population, or the messiness of everyday care?

This is where I share the code behind those questions. Pick a project, look under the hood, and try it with your own questions. I'd love to hear what you find.

**52 research projects · 6 connected directions**

[Clinical NLP](#clinical-nlp) · [Computer Vision & Biomedical Imaging](#biomedical-imaging) · [Trustworthy AI](#trustworthy-ai) · [Prediction Modelling](#prediction-modelling) · [Health Informatics](#health-informatics) · [AI for Health](#ai-for-health)

---

## A few places to begin

<table>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/terry0809000/MIMIC_SBDH"><img src="https://raw.githubusercontent.com/terry0809000/MIMIC_SBDH/main/assets/project-cover.png" width="100%" alt="Social and behavioural determinants from clinical text" /></a>
<p><strong>Social and behavioural determinants from clinical text</strong></p>
<p>How do conventional and transformer models compare for SBDH classification?</p>
<p><a href="https://github.com/terry0809000/MIMIC_SBDH">Explore the code →</a></p>
</td>
<td width="33%" valign="top">
<a href="https://github.com/terry0809000/breast-mri-response-prediction"><img src="https://raw.githubusercontent.com/terry0809000/breast-mri-response-prediction/main/assets/project-cover.png" width="100%" alt="MRI and clinical prediction of pathological complete response" /></a>
<p><strong>MRI and clinical prediction of pathological complete response</strong></p>
<p>What can MRI and clinical information tell us about pathological complete response?</p>
<p><a href="https://github.com/terry0809000/breast-mri-response-prediction">Explore the code →</a></p>
</td>
<td width="33%" valign="top">
<a href="https://github.com/terry0809000/transcriptomic-patient-reuse"><img src="https://raw.githubusercontent.com/terry0809000/transcriptomic-patient-reuse/main/assets/project-cover.png" width="100%" alt="Patient reuse and apparent transcriptomic diagnostic performance" /></a>
<p><strong>Patient reuse and apparent transcriptomic diagnostic performance</strong></p>
<p>How does patient reuse affect apparent transcriptomic diagnostic performance?</p>
<p><a href="https://github.com/terry0809000/transcriptomic-patient-reuse">Explore the code →</a></p>
</td>
</tr>
</table>

## Explore the projects

Choose a direction below. **Project titles open the repository; “Guide” opens the portfolio introduction.** Each project appears once, under its main research direction.

<!-- PROJECT_INDEX_START -->

## Explore the projects

Each project has one home here. Related directions stay visible in its guide and cross-subject labels.

<a id="clinical-nlp"></a>

### Clinical NLP

Clinical and biomedical language sit at the centre of this direction, alongside reading and rationale benchmarks that help examine how language models behave.

| Project | The question behind it |
|:--|:--|
| **[Social and behavioural determinants from clinical text](https://github.com/terry0809000/MIMIC_SBDH)**<br>[Guide](pipelines/MIMIC_SBDH.md) | How do conventional and transformer models compare for SBDH classification? |
| **[Cross-corpus abstract classification](https://github.com/terry0809000/biomedical-abstract-sentence-classification)**<br>[Guide](pipelines/biomedical-abstract-sentence-classification.md) | How do lightweight sentence classifiers transfer between corpora? |
| **[Clinical trial inference: reference and answer-mapping sensitivity](https://github.com/terry0809000/clinical-trial-inference-joint-audit)**<br>[Guide](pipelines/clinical-trial-inference-joint-audit.md) | How do reference choices and answer mapping affect clinical-trial inference? |
| **[Availability-aware source selection for clinical NLP](https://github.com/terry0809000/availability-aware-clinical-nlp)**<br>[Guide](pipelines/availability-aware-clinical-nlp.md) | How does source availability affect clinical NLP evaluation? |
| **[Beyond Macro-F1](https://github.com/terry0809000/beyond-macro-f1-pubmed-rct-public)**<br>[Guide](pipelines/beyond-macro-f1-pubmed-rct-public.md)<br><sub>Also: Trustworthy AI</sub> | Does better classification imply better calibration and perturbation consistency? |
| **[Rationale reliability audit](https://github.com/terry0809000/hatespeechcheck)**<br>[Guide](pipelines/hatespeechcheck.md)<br><sub>Also: Trustworthy AI</sub> | Do supporting rationales remain faithful and robust? |
| **[Reading dynamics with ZuCo 2.0](https://github.com/terry0809000/zuco2-scientific-ml-pipeline)**<br>[Guide](pipelines/zuco2-scientific-ml-pipeline.md)<br><sub>Also: AI for Health</sub> | Can lexical and early-fixation features predict later processing load? |

[↑ Back to directions](#a-few-places-to-begin)

<a id="biomedical-imaging"></a>

### Computer Vision & Biomedical Imaging

Medical images, reconstruction and elastography-derived measurements: useful signals, with explicit limits on what each pipeline actually analyses.

| Project | The question behind it |
|:--|:--|
| **[Selective skin-lesion referral](https://github.com/terry0809000/ham10000-trustworthy-skin-ai)**<br>[Guide](pipelines/ham10000-trustworthy-skin-ai.md) | How do calibration and abstention change model evaluation? |
| **[Excision selection and melanoma assessment](https://github.com/terry0809000/melanoma-excision-selection)**<br>[Guide](pipelines/melanoma-excision-selection.md) | How does excision selection affect melanoma assessment? |
| **[MRI and clinical prediction of pathological complete response](https://github.com/terry0809000/breast-mri-response-prediction)**<br>[Guide](pipelines/breast-mri-response-prediction.md) | What can MRI and clinical information tell us about pathological complete response? |
| **[Color-response sensitivity for pathology error screening](https://github.com/terry0809000/cvpath-color-response-screening)**<br>[Guide](pipelines/cvpath-color-response-screening.md) | Can stain-perturbation responses help screen pathology classification errors? |
| **[MRI calibration-noise analysis](https://github.com/terry0809000/mri-calibration-noise)**<br>[Guide](pipelines/mri-calibration-noise.md) | How does sensitivity-map calibration carry added noise into MRI reconstruction? |
| **[Temporal liver elastography triage](https://github.com/terry0809000/liver-elastography-temporal-triage)**<br>[Guide](pipelines/liver-elastography-temporal-triage.md)<br><sub>Also: Prediction Modelling</sub> | How do temporal evaluation and sensitivity targets affect liver elastography triage? |

[↑ Back to directions](#a-few-places-to-begin)

<a id="trustworthy-ai"></a>

### Trustworthy AI

A strong headline metric is only the beginning. These projects examine calibration, sample reuse, source information and fragile evaluation choices.

| Project | The question behind it |
|:--|:--|
| **[SAFE-LABS](https://github.com/terry0809000/safelabs-icu-lab-deferral)**<br>[Guide](pipelines/safelabs-icu-lab-deferral.md) | How can a selective-prediction policy be tested without overstating safety? |
| **[Source information limits in synthetic validation](https://github.com/terry0809000/synthetic-validation-source-limits)**<br>[Guide](pipelines/synthetic-validation-source-limits.md) | What can synthetic validation establish when source information is limited? |
| **[Outcome ascertainment and transportability in ICU prediction](https://github.com/terry0809000/icu-outcome-ascertainment)**<br>[Guide](pipelines/icu-outcome-ascertainment.md) | How do endpoint recording and observation timing change ICU model evaluation? |
| **[Clinical prediction uncertainty and identification](https://github.com/terry0809000/clinical-uncertainty-identification)**<br>[Guide](pipelines/clinical-uncertainty-identification.md) | Which clinical prediction conclusions can the available evidence identify? |
| **[Universal preservation under stochastic transformations](https://github.com/terry0809000/universal-preservation-theory)**<br>[Guide](pipelines/universal-preservation-theory.md) | When does a shared stochastic observation preserve decision order? |
| **[Fixed-target forecast revisions under sensor outages](https://github.com/terry0809000/fixed-target-forecast-revisions)**<br>[Guide](pipelines/fixed-target-forecast-revisions.md) | How should a fixed-target forecast change when sensor messages arrive late? |
| **[ChronoShield-ICU count-matched temporal evaluation](https://github.com/terry0809000/chronoshield-icu)**<br>[Guide](pipelines/chronoshield-icu.md) | Do clinical timing features add information after measurement counts are matched? |
| **[Relative and absolute augmentation gains under observation loss](https://github.com/terry0809000/clinical-observation-loss-augmentation)**<br>[Guide](pipelines/clinical-observation-loss-augmentation.md) | Does an augmentation gain remain meaningful when absolute predictive performance falls under observation loss? |
| **[Source-only clinical model selection under missingness stress](https://github.com/terry0809000/ehr-missingness-model-selection)**<br>[Guide](pipelines/ehr-missingness-model-selection.md) | Do missingness stress tests change source-only model selection, or do competing rules choose the same candidate? |

[↑ Back to directions](#a-few-places-to-begin)

<a id="prediction-modelling"></a>

### Prediction Modelling

Predictions live in time. I study how clinical models behave when the population, hospital, endpoint or analysis specification changes.

| Project | The question behind it |
|:--|:--|
| **[ARDS / AHRF temporal validation](https://github.com/terry0809000/ards-ahrf-ehr-temporal-validation)**<br>[Guide](pipelines/ards-ahrf-ehr-temporal-validation.md) | How does model performance change across time and ICU databases? |
| **[Temporal screening evaluation](https://github.com/terry0809000/nhanes-temporal-diabetes-screening)**<br>[Guide](pipelines/nhanes-temporal-diabetes-screening.md) | Does model complexity improve probability estimation under temporal shift? |
| **[Extubation transportability](https://github.com/terry0809000/copd-asthma-extubation-transportability)**<br>[Guide](pipelines/copd-asthma-extubation-transportability.md) | How does endpoint construction affect cross-database transport? |
| **[Dynamic AKI prediction](https://github.com/terry0809000/aki-dynamic-prediction-deployment-gated)**<br>[Guide](pipelines/aki-dynamic-prediction-deployment-gated.md) | How do temporal renal models behave under external transport? |
| **[AMI-CS dynamic risk modelling](https://github.com/terry0809000/ami-cs-dynamic-risk-modeling)**<br>[Guide](pipelines/ami-cs-dynamic-risk-modeling.md) | How do shock anchors and dynamic predictors affect cross-database risk modelling? |
| **[Sepsis-to-shock temporal prediction](https://github.com/terry0809000/sepsis-shock-ai-medicine-v9)**<br>[Guide](pipelines/sepsis-shock-ai-medicine-v9.md) | How does temporal landmark modelling transport across ICU databases? |
| **[Specification sensitivity in retrospective ICU evaluation](https://github.com/terry0809000/icu-specification-sensitivity)**<br>[Guide](pipelines/icu-specification-sensitivity.md) | How do analysis specifications change retrospective ICU evaluation? |
| **[Incremental prediction of hypernatremia](https://github.com/terry0809000/hypernatremia-incremental-prediction)**<br>[Guide](pipelines/hypernatremia-incremental-prediction.md) | What does a model add beyond routine sodium measurements? |
| **[Incremental value of vasopressor prediction](https://github.com/terry0809000/vasopressor-incremental-value)**<br>[Guide](pipelines/vasopressor-incremental-value.md) | Do disease-specific treatment patterns add useful mortality predictions? |
| **[Dynamic major adverse kidney-event prediction in T2DM and CKD](https://github.com/terry0809000/t2dm-ckd-dynamic-kidney-risk)**<br>[Guide](pipelines/t2dm-ckd-dynamic-kidney-risk.md) | How does kidney-event prediction change across clinical landmarks when follow-up and cohort eligibility remain explicit? |
| **[AKI progression: transportability and model updating](https://github.com/terry0809000/aki-progression-transportability)**<br>[Guide](pipelines/aki-progression-transportability.md) | What changes when an AKI progression model moves between clinical databases and requires local updating? |

[↑ Back to directions](#a-few-places-to-begin)

<a id="health-informatics"></a>

### Health Informatics

How we collect and record data is part of the story. These workflows connect clinical measurement, population surveys, surveillance and access to care.

| Project | The question behind it |
|:--|:--|
| **[Healthcare access and glucose-testing gaps](https://github.com/terry0809000/brfss-glucose-testing-access)**<br>[Guide](pipelines/brfss-glucose-testing-access.md) | How do healthcare access and glucose-testing gaps vary in public-use survey data? |
| **[Six-hour ICU laboratory prediction](https://github.com/terry0809000/icu-six-hour-lab-prediction)**<br>[Guide](pipelines/icu-six-hour-lab-prediction.md) | What can routinely collected intensive care data tell us about laboratory measurements six hours ahead? |
| **[Temporal measurement and source availability benchmark](https://github.com/terry0809000/icu-temporal-measurement-benchmark)**<br>[Guide](pipelines/icu-temporal-measurement-benchmark.md) | How does measurement timing and source availability shape retrospective ICU evaluation? |
| **[Eating disorder dynamics across everyday moments](https://github.com/terry0809000/eatingdisordermlvar)**<br>[Guide](pipelines/eatingdisordermlvar.md) | How do eating-related symptoms, affect and maladaptive exercise connect across EMA surveys? |
| **[Healthcare affordability and testing gaps](https://github.com/terry0809000/nhis-affordability-testing-gaps)**<br>[Guide](pipelines/nhis-affordability-testing-gaps.md) | When care costs too much, who misses a test? |
| **[Availability-aware EHR modelling](https://github.com/terry0809000/ash-ehr-availability)**<br>[Guide](pipelines/ash-ehr-availability.md) | What changes when a clinical model can use only the information actually available at prediction time? |
| **[Laboratory documentation counts and retrospective recording rules](https://github.com/terry0809000/icu-documentation-counts)**<br>[Guide](pipelines/icu-documentation-counts.md) | When does a laboratory documentation count reflect recording rules rather than a distinct clinical measurement? |
| **[Measurement-aware retrospective ICU prediction](https://github.com/terry0809000/icu-measurement-aware-prediction)**<br>[Guide](pipelines/icu-measurement-aware-prediction.md)<br><sub>Also: Prediction Modelling</sub> | How do measurement patterns affect retrospective ICU prediction? |
| **[Stability and clinical interpretation of kidney risk models](https://github.com/terry0809000/nhanes-kidney-risk-stability)**<br>[Guide](pipelines/nhanes-kidney-risk-stability.md)<br><sub>Also: Prediction Modelling</sub> | How stable and clinically interpretable are kidney risk models? |
| **[Respiratory surveillance](https://github.com/terry0809000/bmc-dm-prediction-one-week)**<br>[Guide](pipelines/bmc-dm-prediction-one-week.md)<br><sub>Also: AI for Health</sub> | Can aggregate surveillance signals anticipate next-week escalation? |

[↑ Back to directions](#a-few-places-to-begin)

<a id="ai-for-health"></a>

### AI for Health

From molecular variation to sleep and movement, I build tools to explore health questions across different scales.

| Project | The question behind it |
|:--|:--|
| **[TRACE-Fib](https://github.com/terry0809000/trace-fib-pipeline)**<br>[Guide](pipelines/trace-fib-pipeline.md) | How do normalization and study weighting affect cross-organ transfer? |
| **[Sleep-EDF staging](https://github.com/terry0809000/sleepingedf)**<br>[Guide](pipelines/sleepingedf.md) | How do local context, channel choice and smoothing affect sleep staging? |
| **[Preprocessing sensitivity of glomerular BEX3 prioritisation](https://github.com/terry0809000/dkd-bex3-preprocessing)**<br>[Guide](pipelines/dkd-bex3-preprocessing.md) | How sensitive is glomerular BEX3 prioritisation to preprocessing choices? |
| **[Adaptive versus fixed smartwatch task acquisition](https://github.com/terry0809000/pads-adaptive-acquisition)**<br>[Guide](pipelines/pads-adaptive-acquisition.md) | How does adaptive smartwatch task acquisition compare with fixed acquisition? |
| **[Selective review and total sleep time estimation](https://github.com/terry0809000/sleep-duration-selective-review)**<br>[Guide](pipelines/sleep-duration-selective-review.md) | Which sleep epochs deserve review when estimating total sleep time? |
| **[ECG reliability screening with fixed calibration](https://github.com/terry0809000/earlybird-ecg-reliability)**<br>[Guide](pipelines/earlybird-ecg-reliability.md) | Can fixed calibration recognize perturbed ECG inputs without mistaking simulated labels for clinical quality? |
| **[Objective physiological phenotyping: Sleep-EDF module](https://github.com/terry0809000/objective-physiological-phenotyping)**<br>[Guide](pipelines/objective-physiological-phenotyping.md) | What can objective sleep architecture reveal without turning physiological disruption into a psychiatric label? |
| **[Patient reuse and apparent transcriptomic diagnostic performance](https://github.com/terry0809000/transcriptomic-patient-reuse)**<br>[Guide](pipelines/transcriptomic-patient-reuse.md)<br><sub>Also: Trustworthy AI</sub> | How does patient reuse affect apparent transcriptomic diagnostic performance? |
| **[False positives and sample reuse in pulmonary-nodule assessment](https://github.com/terry0809000/pulmonary-nodule-transcriptomic-audit)**<br>[Guide](pipelines/pulmonary-nodule-transcriptomic-audit.md)<br><sub>Also: Trustworthy AI</sub> | How do false positives and sample reuse affect pulmonary-nodule assessment? |

[↑ Back to directions](#a-few-places-to-begin)

<!-- PROJECT_INDEX_END -->

---

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
