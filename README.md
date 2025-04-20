# adage.usekarma.dev

This repository contains the public documentation site for **Adage**, the infrastructure deployment framework that powers [Karma](https://usekarma.dev).

The site is built with [Hugo](https://gohugo.io/) using the [Hugo Book](https://github.com/alex-shpak/hugo-book) theme.

You can view the live site at:

**[https://adage.usekarma.dev](https://adage.usekarma.dev)**

---

## About Adage

Adage enables infrastructure-as-consequence — where systems are deployed based on configuration, not imperative logic.

Features:
- Modular, composable Terraform components
- Configuration-driven deployments using AWS Parameter Store
- Support for multi-account, multi-environment AWS orgs
- Built-in traceability and controlled runtime updates

---

## Repository Structure

```bash
.
├── content/           # Markdown-based site content
├── static/            # Logo and asset files
├── themes/            # Hugo Book theme (can be submodule or vendored)
├── config.toml        # Hugo site configuration
└── README.md          # This file
```

---

## Deployment

This site is deployed via the `publish_site.py` script in the [`karma-dev-config`](https://github.com/usekarma/karma-dev-config) repository.

To publish:

```bash
AWS_PROFILE=prod-iac ./scripts/publish_site.py --nickname adage-usekarma-dev
```
