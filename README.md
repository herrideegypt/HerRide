# HerRide Egypt Website

HerRide Official Website & System.

## Deployment model
- `main` is the production source branch.
- Cloudflare Pages should be connected to this repository and deploy from `main`.
- Website history is preserved through Git commits so a previous working version can be restored safely.

## Security
Do not commit passwords, private API keys, service-account JSON files, or other secrets. Use Cloudflare/GitHub environment variables for secrets.
