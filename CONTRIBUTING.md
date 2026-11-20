# Contributing to Selō Consulting projects

Thanks for your interest. These guidelines apply to every repository in the `selo-consulting` organization unless a repository provides its own.

## Before you start

- **Questions or ideas:** open an issue so we can discuss before you invest time in a change.
- **Security issues:** don't open a public issue — follow [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository (or create a branch if you're an org member).
2. Keep changes focused — one logical change per pull request.
3. Add or update tests and docs alongside code changes.
4. Make sure existing tests and linters pass.
5. Open a pull request describing what changed and why.

## Ground rules for our codebases

- **No secrets in code, ever.** Credentials belong in a secrets manager (e.g. Azure Key Vault) accessed via managed identity — never in source, config files, or test fixtures.
- **Synthetic data only.** Don't commit real client, employer, or personal data. Demos and tests use generated data.
- **Config over code.** Prefer making behaviour configurable over hard-coding client-specific logic.
- **Deterministic numbers.** KPI calculations live in tested code, not in prompts.

## Conduct

All participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
