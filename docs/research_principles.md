# Research principles

## Scope
This project studies the robustness of multilingual NLP systems on Hindi-English code-mixed social-media text, with particular attention to Romanization/transliteration, spelling variation, normalization, and realistic textual noise.

## Evidence standard
Every numerical result in the final study must come from an executed experiment. The repository must preserve enough information to reproduce the result: dataset provenance, code version, environment, model identifier/version, configuration, seed, and output artifact.

## Novelty standard
Do not claim that a method, benchmark, or finding is the first unless the literature review supports that statement. The contribution should be framed as an empirical finding or methodological comparison that is actually demonstrated by the experiments.

## Data integrity
Use public datasets only when their provenance and access terms are documented. Do not commit restricted/raw datasets when their terms prohibit redistribution. Keep source URLs, access dates, dataset identifiers, preprocessing decisions, and any license/terms notes in `data/README.md`.

## Experimental discipline
1. Define train/validation/test splits before looking at test results.
2. Prevent duplicate or near-duplicate leakage across splits.
3. Fit learned preprocessing only on training data when applicable.
4. Keep the test set untouched until evaluation.
5. Use consistent evaluation code across models and conditions.
6. Record failures and deviations from the planned protocol.
7. Report unfavorable or null findings as well as improvements.

## Reproducibility
All executable experiments should have a deterministic configuration where practical. When GPU or library nondeterminism prevents exact repeatability, record seeds, versions and hardware/software details and state the limitation.

## Repository policy
No passwords, API keys, private data, or restricted datasets should be committed. Dataset download scripts should prefer the original provider or documented source rather than redistributing source data.
