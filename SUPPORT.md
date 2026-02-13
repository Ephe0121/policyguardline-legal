# PolicyGuardline Support

## Support channels

- Email: support@policyguardline.com
- Response target: within 2 business days

## What to include in your ticket

- Installation ID
- Repository owner/name
- Pull request URL
- Time of issue (UTC)
- Relevant check run output

## Common troubleshooting

1. Ensure `PolicyGuardline` is configured as a required status check.
2. Confirm webhook delivery is successful in GitHub App settings.
3. Verify `.prguard.yml` syntax and rule fields.
4. Confirm app permissions include Checks write and Pull requests read.

## Status

Operational health endpoint:

- `GET /health` on your deployed API Gateway URL
