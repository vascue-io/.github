# Security policy

Vascue welcomes responsible reports that help us protect healthcare providers and patients.

## Report a vulnerability privately

Do not open a public GitHub issue for a suspected vulnerability.

Email [hello@vascue.io](mailto:hello@vascue.io) with the subject line "SECURITY REPORT". Include:

- the affected Vascue service or public repository;
- a concise description of the issue and its potential impact;
- reproducible steps using synthetic or redacted data;
- relevant request identifiers, timestamps, or screenshots with sensitive values removed; and
- a safe way to contact you.

You may also consult the [Vascue Trust Center](https://trustcenter.vascue.io/) and [security page](https://www.vascue.io/security).

## Never include sensitive data

Do not send or publish:

- patient names, contact details, policy numbers, or clinical information;
- real referral letters, invoices, claim forms, or medical images;
- clinic credentials or practice-management API keys;
- access tokens, session cookies, private keys, or passwords; or
- production database contents.

Use synthetic examples and redact secrets and identifiers. If sensitive data has already been exposed, stop sharing it and contact Vascue privately with only the minimum information needed to locate the exposure.

## Scope and authorization

Do not access, alter, download, or retain data that does not belong to you. Do not disrupt services, test against real patients, perform social engineering, or use automated testing that could degrade availability.

This policy does not grant authorization to test Vascue systems. Coordinate with Vascue before performing security research beyond passive inspection of public resources.

Vascue will review good-faith reports and coordinate next steps through a private channel.
