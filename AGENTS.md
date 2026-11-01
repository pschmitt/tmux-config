# Agent guidance

This repository contains tmux configuration and plugin references.

## Development

- Keep personal paths, host names, and session-specific details out of shared examples.
- Treat plugin submodules as external dependencies; initialize them only when needed to work on plugin integration.
- No repository-wide test runner is present. Review configuration syntax and validate in a disposable tmux server/session.

## CI

- Before changing GitHub Actions, inspect the current guidance in `pschmitt/ci-workflows`. Use `@main` in every `uses:` reference to a shared workflow or action.
