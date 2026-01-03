# CORE VERTICAL — Scientific Research

This repository defines the Scientific Research vertical lens for the CORE platform.

It provides research-oriented workflows, tooling, and interpretation layers on top of CORE physics engines.

## Scope
- Experiment lifecycle workflows
- Reproducibility and replication tooling
- Artifact review and comparison surfaces
- Publication-grade data packaging
- Peer review and validation interfaces

## Non-Scope
- No physics solvers
- No engine logic
- No identity or authentication authority
- No governance authority

## Architecture Position
This vertical consumes outputs from CORE engines such as:
ARES, HYDRA, THERMOS, MAGNETAR, LITHOS, ATMOS, KINETIC, CRYSTAL, SIGNAL, and RGSR.

## Governance
This repository inherits all authority from `core-platform`.
Any conflict with CORE governance renders the implementation invalid.
