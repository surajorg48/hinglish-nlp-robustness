# Robustness of Multilingual NLP Models to Code-Mixing and Romanization

Research repository for an empirical study of Hindi-English code-mixed social-media text.

**Author:** Suraj Choudhari  
**Academic affiliation:** Dr. Babasaheb Ambedkar Marathwada University, Chhatrapati Sambhajinagar, Maharashtra, India  
**Degree:** M.Sc. Information Technology, 2024  
**ORCID:** 0009-0003-9536-907X  
**Email:** surajorg47@gmail.com

## Research status

This repository is the reproducibility workspace for the study. Numerical findings will be added only after the corresponding experiments have been executed and independently checked.

## Working research question

How robust are multilingual NLP models when Hindi-English code-mixed social-media text is affected by romanization, spelling variation, normalization choices, and other realistic forms of textual noise?

## Planned study

The experimental design will compare carefully justified classical and multilingual transformer baselines under controlled text conditions, using fixed train/validation/test protocols, multiple random seeds where feasible, macro-F1 and complementary metrics, robustness/degradation measures, and linguistic error analysis.

## Reproducibility principles

- Do not fabricate or infer numerical results.
- Record dataset provenance, preprocessing rules, model versions, seeds, and environment details.
- Do not commit restricted datasets or credentials.
- Keep generated results traceable to the scripts that produced them.
- Report negative and unexpected findings rather than selecting only favorable outcomes.

## Planned structure

```text
configs/          Experiment configurations
src/              Source code
notebooks/        Exploratory and reproducible notebooks
experiments/      Experiment launch scripts and protocols
data/             Dataset documentation; raw restricted data is not committed
results/          Verified experiment outputs
figures/          Research figures
paper/            Manuscript-support materials
docs/             Research design, provenance, and reproducibility notes
```

## Current status

Research design and literature review are in progress. Results are intentionally absent until experiments are run.
