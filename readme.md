# Lead Lifecycle ADF – Publish Branch

## Overview

This branch contains the published Azure Data Factory ARM templates generated automatically by ADF.

It is used for deployment and CI/CD purposes.

## Contents

- ARMTemplateForFactory.json
- ARMTemplateParametersForFactory.json
- Linked templates
- Global parameters

These files are auto-generated when clicking "Publish" in ADF Studio.

## Purpose

The adf_publish branch is intended for:

- Production deployment
- Infrastructure-as-Code (IaC)
- CI/CD pipelines
- ARM template-based releases

## Deployment

To deploy this factory:

1. Use ARMTemplateForFactory.json
2. Provide values in ARMTemplateParametersForFactory.json
3. Deploy via:
   - Azure Portal
   - Azure CLI
   - Azure DevOps pipeline
   - GitHub Actions

Note:
Do not manually edit files in this branch.
All changes should be made in the main branch via ADF Studio and then published.
