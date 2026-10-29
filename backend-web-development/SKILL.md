---
name: backend-web-development
description: Design or change server-side web behavior, APIs, data models, authentication, or integrations.
---

# Backend Web Development

Implement backend changes that fit the project's architecture and preserve clear, dependable contracts.

## Workflow

- Inspect service layout, API conventions, data model, authentication, configuration, and migrations before editing.
- Confirm callers, expected inputs and outputs, permissions, and failure behavior.
- Validate untrusted input at the boundary. Enforce authorization on the server for protected operations.
- Keep secrets out of source, responses, and logs. Use the project's established secret configuration.
- Preserve compatibility where possible. For breaking schema or API changes, identify affected callers and a safe migration path.
- Handle timeouts, retries, duplicate requests, and partial failures where relevant.
- Run focused checks consistent with the project and report exactly what was verified.

## Boundaries

- Do not assume a specific framework, database, or cloud provider.
- Do not make destructive data changes or deploy services without authorization.
- Do not claim a security property or successful migration without evidence.

## Provenance

Original instructions authored for this team, based on the Backend Engineer role description in this conversation. No third-party skill files were copied.
