# SILENCE.OBJECTS

Deterministic behavioral signal intelligence infrastructure.

SILENCE.OBJECTS documents an ND-first, privacy-by-design system for structured behavioral signals: deterministic event logic, federated processing, audit-ready provenance.

This repository is the **public citation surface**. It is not the product runtime and not Enterprise.

## What this is

A contract-first, fixture-first open layer: definitions, glossary, FAQ, method notes, and a machine-readable agent feed.

## What this is not

Not a medical device. Not diagnosis. Not therapy. Not a score of a person. Not `03_ee/`.

Disclaimer: *Non-clinical behavioral protocol. No diagnosis. No therapy.*

## Surfaces

| Path | Job |
|---|---|
| [faq.md](faq.md) | one question, one answer |
| [glossary.md](glossary.md) | canonical terms |
| [method/effectlog.md](method/effectlog.md) | append-only provenance |
| [research-protocols/iti-ans-v1.md](research-protocols/iti-ans-v1.md) | protocol-first research note |
| [agent-feed.json](agent-feed.json) | extractable claims |
| [claims/public-claim-manifest.json](claims/public-claim-manifest.json) | allowed public sentences |

Canonical web target: `https://patternslab.org` (deploy this tree). Until DNS is live, cite this repo.

## Publication zones

| Zone | Public |
|---|---|
| Open-core | contracts, taxonomy, FSM, synthetic fixtures |
| Research-publication | only after review + release manifest |
| Enterprise / private | never |

Direction: `03_ee` → sanitized artefact → governance review → public release. Never the reverse.

Every numeric claim in public text needs a label: `MEASURED` | `MODELED` | `HYPOTHESIS` | `SYNTHETIC` | `CANONICAL`.
