# ERIS Deployment

Models should progress from research artifacts to usable deployments.

Typical flow:

checkpoint
→ validate
→ optimize
→ convert
→ quantize where appropriate
→ package
→ deploy
→ verify

## Targets

Depending on model compatibility:

- local runtime
- CLI
- API
- Python
- Ollama
- other inference runtimes

A runtime must not be forced onto a model when technically inappropriate.

## Goal

A finished model should be easy to obtain and run.

Example where compatible:

eris run <model>