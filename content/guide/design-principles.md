---
title: "Design Principles"
weight: 1
---

# Design Principles

Adage is built on the idea of **infrastructure as consequence** — where infrastructure is shaped by declarative config, and each deployment traces its origin and dependencies.

Core principles:

- **Config-first**: Infra is defined outside of the codebase.
- **Modular**: Components are reusable, composable, and independently testable.
- **Traceable**: Every deployed object is linked to its config and lineage.
- **Environment-aware**: Deployment logic adapts to the AWS account and context.
