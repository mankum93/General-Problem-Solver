# Architecture

GPSIF has three public layers.

```mermaid
flowchart TB
    R[README and public docs] --> M[Machine runtime]
    M --> C[Canonical framework standards]
    M --> P[Capability and domain profiles]
    M --> T[Optional task-graph expert pack]
    C --> V[Validators, schemas, templates, and release records]
```

## Public layer

The public layer explains what the framework is, who should use it, and how to start.

## Machine runtime layer

The runtime layer gives agents compact operating rules so they do not need to load every canonical file for ordinary use.

## Canonical framework layer

The canonical layer contains the full standards, profiles, schemas, templates, QA records, and release contract material.

## Design rule

Use the lightest execution form that still preserves rigor, evidence, validation, and trustworthy conclusions.
