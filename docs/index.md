# Azure Enterprise Admin Guide & Toolkit

This repository is evolving from a broad Azure reference into a **guide + toolkit** for enterprise administrators.

## Two layers

### 1. Guide
Architecture and operational guidance across core Azure domains:
- `architecture/`
- `identity/`
- `networking/`
- `compute/`
- `storage/`
- `database/`
- `security/`
- `automation/`
- `monitoring/`
- `hybrid/`
- `governance/`
- `devops/`

### 2. Toolkit
Practical files you can run, adapt, and extend:
- `scripts/` for operational automation
- `queries/` for Azure Resource Graph and KQL
- `bicep/` for policy-as-code and landing-zone building blocks
- `samples/` for example outputs and screenshots
- `.github/workflows/` for validation and automation

## Featured starting points

### Tenant inventory
- Query: `queries/resource-graph/tenant-inventory.kql`
- Export script: `scripts/inventory/export-tenant-inventory.ps1`
- Sample output: `samples/reports/tenant-inventory-sample.csv`

### Policy starter pack
- `bicep/policy-assignments/allowed-locations.bicep`
- `bicep/policy-assignments/require-tags.bicep`
- `bicep/policy-assignments/deny-public-ip.bicep`

### Landing zone starter
- `bicep/landing-zone/main.bicep`

## Next recommended repo actions
1. Move existing markdown topic folders under `docs/` when you are ready for a cleaner structure.
2. Promote this positioning into the root `README.md`.
3. Add screenshots under `samples/screenshots/`.
4. Add more scripts for governance, monitoring, and RBAC export.

## Audience
- Azure consultants
- enterprise administrators
- cloud architects
- platform engineers
