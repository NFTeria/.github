# Security Policy

## Reporting a vulnerability

Email **security@nfteria.click** with:
- A description of the vulnerability + affected component
- Reproduction steps or proof-of-concept
- Your name + handle if you want public credit

We aim to:
- Acknowledge within 48 hours
- Assess + scope within 5 business days
- Patch + disclose responsibly (90-day default window, faster for critical)

## Scope

In scope: the GitHat-platform apps under this organization.
Out of scope: third-party services (Stripe, AWS, SES), social-engineering, physical, denial-of-service.

## Bug bounty

We do not currently run a paid bounty program but happily credit reporters in patch notes.

## Cryptography + identity

GitHat tokens are RS256-signed via AWS KMS. Public verification material is at `/.well-known/jwks.json` on the issuer. CAA records lock cert issuance to AWS Certificate Manager only.

## Preferred languages

English.

