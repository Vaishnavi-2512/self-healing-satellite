# Security and safe configuration

This repository contains research and simulation code. Before running integrations:

- Never commit API keys, passwords, tokens, or private credentials.
- Keep `.env` local; use `.env.example` as the configuration template.
- Keep model checkpoints, generated datasets, and large outputs outside version control unless they are intentionally released.
- Review third-party model and dataset licenses before redistribution.
- Treat generated reports and external-service integrations as untrusted inputs until validated.

If a credential is accidentally committed, revoke or rotate it immediately and remove it from the repository history using an appropriate secret-removal workflow.
