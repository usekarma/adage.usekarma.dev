---
title: "Deploying a Component"
weight: 3
---

# Deploying a Component

To deploy a component:

1. Define a config file in the config repo
2. Use the `deploy_config.py` script to publish the config to Parameter Store
3. Run Terraform (or Terragrunt) using the resolved configuration

Components can be deployed individually or as part of an orchestrated flow.
