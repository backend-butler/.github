# Contributing

Thanks for helping. A few things keep the project easy to maintain:

- **Open an issue before a large change**, so we can agree on the approach first.
- **One change per pull request**, with tests. CI runs typecheck, tests and build; it must pass.
- **No new dependencies without discussion.** Every package is something users install and we must audit.
- **Safety model.** Anything that lets the agent act must declare whether it runs at once, asks first, or is never allowed. When unsure, it asks first.
- **Security issues** go through private reporting (see SECURITY.md), not issues or pull requests.

By contributing you agree your work is released under the repository's MIT license.
