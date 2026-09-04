# Experimental protocol — draft

This file records the planned protocol before numerical results are collected. It is intentionally a draft and must be updated after the literature and dataset audit.

## Core question

Measure how multilingual NLP model performance changes when Hindi-English code-mixed social-media text is presented in realistic alternative surface forms, including romanization/transliteration and spelling or normalization variation.

## Planned comparisons

- Classical text baseline(s) for a low-compute reference.
- One or more justified multilingual transformer baselines selected after literature review.
- Raw/original text versus carefully defined normalized or perturbed conditions.

## Evaluation

Primary metric: macro-F1. Secondary metrics should include accuracy and per-class precision/recall where appropriate. Robustness should be expressed as absolute and relative performance change from the clean/reference condition. Confidence intervals and significance testing will be used only where the design supports valid inference.

## Leakage controls

- Establish splits before test evaluation.
- Deduplicate before splitting when duplicate identification is possible.
- Do not fit vocabulary, normalization dictionaries, or other learned transformations on test data.
- Keep test labels hidden from model selection.

## Replication

At least three random seeds should be considered for stochastic model training when computationally practical. Each run must record model identifier, library versions, seed, configuration, hardware, runtime and output metrics.

## Result rule

No result belongs in the manuscript until it exists as an output of an executed experiment and can be traced back to the repository code/configuration.
