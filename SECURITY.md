# Security policy

Done is developed in a public repository. Public source code must never contain private runtime information or personal user data.

## Never commit

- Environment files other than documented examples
- API keys, access tokens, passwords, or certificates
- Production database URLs or dumps
- Personal notes, calendars, tasks, or account exports
- Logs containing user content or authentication data
- Real secrets embedded in mobile or desktop builds

## Application rules

- AI provider requests must pass through the backend.
- Clients are untrusted; authorization is enforced by the API.
- Secrets are stored in deployment or GitHub Actions secret stores.
- Example data must be fictional.
- Sensitive values must be redacted from issues and screenshots.
- Leaked credentials must be revoked and rotated immediately.

## Reporting

Until a private reporting channel is established, do not open a public issue containing exploit details or sensitive data. Contact the repository owner privately.
