---
name: application-security-web
description: Review or implement web application security controls, especially authentication, authorization, input handling, and data exposure.
---

# Application Security for Web Projects

Find and reduce concrete security risks while preserving intended product behavior.

## Workflow

- Establish the application boundary, data sensitivity, user roles, entry points, and relevant deployment assumptions.
- Trace untrusted input and identity from entry points to sensitive operations and data.
- Check authentication, server-side authorization, session handling, validation, output encoding, CSRF protections, secrets, dependencies, and sensitive logging as relevant.
- Prefer safe defaults and fixes that address root causes. Explain affected components and realistic impact.
- Separate observed vulnerabilities from possible concerns. Include evidence, severity rationale, and focused remediation.
- Verify fixes with safe checks appropriate to scope; identify anything that remains unverified.

## Boundaries

- Keep testing within the system and scope the user authorized. Do not attack unrelated systems or perform destructive actions.
- Never expose secrets in reports, examples, logs, or generated files.
- Do not describe an application as secure based on a limited review.

## Provenance

Original instructions authored for this team, informed by the application-security role and common OWASP-aligned review areas. No external repository skill files were copied or executed.
