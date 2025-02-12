# Azure Storage Deployment with GitHub Actions

This repository sets up a CI/CD pipeline using GitHub Actions to automatically deploy website content to **Azure Blob Storage**.

## Deployment Process

1. Push changes to the `main` branch.
2. GitHub Actions will trigger the workflow.
3. Files will be uploaded to **Azure Storage**.

## Setup Instructions

- Ensure the following **GitHub Secrets** are set:
  - `AZURE_CLIENT_ID`
  - `AZURE_CLIENT_SECRET`
  - `AZURE_TENANT_ID`
  - `AZURE_SUBSCRIPTION_ID`
  - `AZURE_STORAGE_ACCOUNT`
  - `AZURE_STORAGE_KEY`
  - `AZURE_CONTAINER_NAME`

## Files Included

- `index.html` - Basic webpage.
- `.github/workflows/azure.yaml` - Deployment workflow.

