# ERIS Data

Data quality matters more than raw quantity.

Track:

- dataset name
- version
- source
- provenance
- license/usage conditions
- collection date
- processing
- filtering
- hashes where useful
- intended purpose

## Pipeline

raw
→ inspect
→ clean
→ filter
→ validate
→ split
→ train/evaluation

Evaluation/test data must be protected from accidental training contamination.

Do not blindly train on low-quality or unverified generated data.