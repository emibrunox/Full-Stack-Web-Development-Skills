---
name: devops-cloud-web
description: Build, deploy, or operate web applications, including CI, infrastructure, observability, and release safety.
---

# DevOps and Cloud for Web Projects

Make web delivery reproducible and observable while respecting the project's environment and release controls.

## Workflow

- Inspect the existing build, CI, hosting, infrastructure-as-code, environment configuration, monitoring, and rollback path.
- Confirm the target environment and distinguish local, preview, staging, and production.
- Prefer repeatable, version-controlled configuration and least-privilege access.
- Keep credentials in the approved secret store; never commit secrets or print them in logs.
- Consider health checks, useful logs, metrics, backups, dependency availability, and recovery for the service being changed.
- Estimate operational or cost impact when capacity, storage, or paid resources may change.
- Verify the target state from deployment or service evidence and report rollback options and uncertainty.

## Boundaries

- Do not provision paid resources, alter production, or deploy without explicit authorization.
- Do not assume a cloud provider; follow the user's selected platform.
- Do not claim deployment succeeded based only on a local build.

## Provenance

Original instructions authored for this team, based on the DevOps and Cloud Engineer role description in this conversation. No third-party skill files were copied.
