# PolicyGuardline Privacy Policy

Effective date: 2026-02-13

PolicyGuardline processes repository metadata required to evaluate pull request policies.

## Data we process

- Pull request metadata (title, branch, labels, review state)
- Changed file paths from pull requests
- Repository metadata (owner/name/id)
- GitHub installation metadata
- Marketplace subscription metadata (plan and billing state)

## Data we do not collect

- Source code contents beyond API responses needed for rule evaluation
- Personal data unrelated to GitHub account identity
- Passwords or payment card information

## Storage and retention

- Event dedupe keys are stored with TTL.
- Repository config cache entries are stored with TTL.
- Installation and marketplace records are stored for operational continuity.

## Security

- Webhooks are verified using HMAC SHA-256 signatures.
- GitHub App private keys and webhook secrets are stored in AWS Secrets Manager.
- Access is limited by least-privilege IAM policies.

## Third-party processors

- GitHub (event source, API provider, marketplace billing)
- AWS (compute, queues, storage, secrets, logging)

## Contact

For privacy requests, contact: support@policyguardline.com
