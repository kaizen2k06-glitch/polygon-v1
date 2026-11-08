# Security and data handling

These are commitments for the design; items marked *(planned)* are not yet implemented.

- **Least privilege:** request only the scopes listed in ZOMATO-INTEGRATION.md.
- **No secrets in git:** tokens, keys and `.env` files are git-ignored; secrets live in the OS keychain / secure storage on device and a secret manager on any server.
- **User-held credentials:** each user signs in themselves; tokens are stored encrypted on device and revocable. *(planned)*
- **Confirmation before money moves:** no order is placed without explicit user confirmation of items and total.
- **Minimal data retention:** audio is processed transiently and not stored by default; transcripts and order data are not logged beyond what is needed for debugging, with PII redacted. *(planned)*
- **Transport:** TLS for all network traffic.
- **Third parties:** speech and LLM providers receive only what is needed for the request; no data is sold or used for advertising.
- **Dependencies:** pinned, scanned (Dependabot / secret scanning enabled on the repo). *(planned)*
- **Disclosure:** see /SECURITY.md.
