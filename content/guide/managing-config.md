---
title: "Managing Config"
weight: 4
---

# Managing Config

All infrastructure in Adage is driven by config files stored in a Git-backed config repository.

Each config file corresponds to a specific component instance and lives under a path like:

```
iac/prod/serverless-site/example-site/config.json
```

This config is published to Parameter Store and used to control when and how a component is deployed.
