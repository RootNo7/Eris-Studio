# ERIS Architecture

ERIS should be modular.

The exact architecture is not permanently predetermined.

Possible components include:

- model systems
- shared infrastructure
- memory
- retrieval
- tools
- model communication
- orchestration
- training
- evaluation
- environments
- deployment
- ERIS Studio

## Architectural rule

Choose architecture based on evidence and requirements.

Do not assume:

- one giant model is always best;
- many independent models are always best;
- transformers are always best;
- every specialist needs to be large;
- every capability belongs inside the base model.

Architecture may evolve.

## Model relationships

Models may be:

- independent;
- based on a shared foundation;
- specialist models connected through common infrastructure;
- dynamically coordinated.

Use the simplest structure that works.

## Shared infrastructure

Shared components should exist when they provide genuine value.

Potential shared systems:

- model registry
- configuration
- logging
- experiment tracking
- evaluation
- deployment
- identity
- permissions
- memory
- communication protocols