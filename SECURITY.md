# Security Policy (GS1 Switzerland)

This document defines the default security policy for repositories under the **GS1-Switzerland** GitHub organization.

## Repository-specific policies take precedence

Some repositories may contain a repository-specific `SECURITY.md` (in the repository root, `docs/`, or `.github/`).
If a repository contains its own `SECURITY.md`, **that repository-specific policy overrides this organization default** for that repository.

If a repository does **not** contain a `SECURITY.md`, this organization-wide policy applies.

## Reporting a vulnerability

Please report security vulnerabilities **privately**. Do not open public GitHub issues for security-sensitive findings.

**Preferred channel**
- Email: it@gs1.ch
- Subject: `SECURITY: <repository> - <short summary>`

**Include**
- Repository name and affected component(s)
- Clear description of the issue and potential impact
- Steps to reproduce or proof-of-concept (if available)
- Any known mitigations/workarounds
- Your contact information for follow-up

If you are unsure whether your finding is security-relevant, report it anyway.

## Response targets

We aim to:
- Acknowledge receipt within **3 business days**
- Provide an initial assessment within **10 business days**
- Share an expected remediation timeline once triaged

These targets may vary depending on severity, complexity, and maintainership capacity.

## Coordinated disclosure

We follow coordinated disclosure principles:
- Please allow reasonable time for investigation and remediation before public disclosure.
- We will coordinate disclosure timing with the reporter when possible.
- If we determine the report is not a security issue, we will explain why.

## Scope

This policy applies to:
- Code, configurations, and documentation hosted in GS1-Switzerland repositories
- Release artifacts published via GS1-Switzerland repositories (if any)

Out of scope (unless explicitly stated by a repository-specific policy):
- Findings that require physical access to devices/infrastructure
- Social engineering, phishing, or spam campaigns
- Vulnerabilities in third-party services or dependencies without a demonstrable impact on GS1-Switzerland repository code
- Denial-of-service reports that do not demonstrate a realistic and actionable impact

## Supported versions

Unless a repository-specific policy states otherwise:
- The default supported version is the latest version on the default branch.
- Security fixes may be provided via commits, tags, or releases depending on repository type.

## Security hardening expectations (contributors)

Contributors are expected to:
- Avoid committing secrets (API keys, passwords, private certificates)
- Use least-privilege configuration and secure defaults
- Keep dependencies current where applicable
- Document security-relevant configuration options where needed

If you accidentally commit a secret, report it immediately using the channel above.

## Safe harbor

We consider good-faith security research and responsible reporting under this policy as authorized.
Do not:
- Access data not belonging to you
- Disrupt services or degrade availability
- Exfiltrate data beyond what is necessary to demonstrate impact

## Credits

If you want to be credited for your report, please indicate the name/handle and link to use.
