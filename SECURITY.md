# Security policy

Backend Butler gives an AI agent access to real devices and servers, so security reports are taken seriously.

## Reporting

Use **Security → Report a vulnerability** on the affected repository. Please do not open a public issue.
Include what you did, what happened, and the version. You should hear back within a week.

## Supported versions

Only the latest release of each repository gets fixes.

## In scope

- The agent acting without the approval it should have needed, or acting on instructions found in data.
- Links or pages that make Butler do something without you tapping it.
- Credentials or chat content reachable by someone who should not have them.
- The `bb` brokers allowing an operation, host or credential outside their registry.
