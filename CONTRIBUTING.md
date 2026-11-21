# Contributing

Thank you for wanting to help. These projects are small and maintained in spare time, so a short conversation first saves everyone work.

## Before you start

- **Bugs:** open an issue with the bug report form. Say what you did, what happened, what you expected, and which version you ran.
- **Changes:** open an issue describing the change before writing it, so we can agree on the shape. Small fixes (a typo, a broken link) can go straight to a pull request.
- **Security problems:** never in a public issue. See [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository and branch from `main`.
2. Follow the project's own README for setup and its checks: each repository lists the commands its continuous integration runs.
3. Keep the change to one purpose, with tests for what it changes.
4. Write commit messages as [Conventional Commits](https://www.conventionalcommits.org/) (`fix: ...`, `feat: ...`, `docs: ...`).
5. Add a line to `CHANGELOG.md` under `[Unreleased]` for anything a user would notice.
6. Open the pull request against `main` and fill in its template.

Continuous integration runs on the maintainers' own machines, so a pull request from a fork waits for a maintainer to approve its first run.

## Licence

Each repository states its licence in its `LICENSE` or `LICENCE` file. By contributing, you agree that your contribution is released under that licence.

## Conduct

Everyone taking part agrees to the [Code of Conduct](CODE_OF_CONDUCT.md).
