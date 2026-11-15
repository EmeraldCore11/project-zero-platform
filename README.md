# Project Zero — Platform Infrastructure

This repository is for universal platform capabilities shared across Project Zero worlds, adventures, users, creators, and modules.

## Intended scope

Candidate service domains include:
- identity and account integration;
- universal authorization and permission evaluation;
- persistence, synchronization, and data management;
- stable unique identities and ownership/provenance;
- search and indexing;
- events, communication, notifications, and activity feeds;
- moderation, reporting, and audit history;
- backup, recovery, lifecycle, and dependency management;
- validation and security support.

The approved specifications determine exact requirements and staging. This list is an architectural orientation, not implementation authorization.

## Boundary rules

- Expose stable, documented contracts to other domains.
- Do not embed world-specific gameplay rules or creator-defined content.
- Do not bypass protected engine-core enforcement.
- Dependency resolution may identify and explain conflicts; it must not silently install, remove, or change dependencies.
- Preserve ownership, permission, provenance, version, and audit information where required by the approved specifications.

## Before implementation

Read the master repository's authoritative documents and Replit Agent guardrails. If a required source is missing, request it rather than inventing requirements.

See the master repository: https://github.com/EmeraldCore11/project_zero
