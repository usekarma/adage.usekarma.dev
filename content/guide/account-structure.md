---
title: "Account Structure"
weight: 2
---

# Account Structure

Adage supports multi-account AWS environments via Organizations and named environments (e.g., `dev`, `prod`).

Each account is bound to an environment configuration, defined centrally and distributed via Parameter Store.

Accounts are expected to be grouped by environment (e.g., `dev-iac`, `prod-lambda`) and adhere to the principle of least privilege across environments.
