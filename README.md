# Xata GitHub Actions Examples

> A comprehensive guide and examples for using [Xata](https://xata.io) database platform with GitHub Actions for CI/CD workflows, database migrations, and automated operations.

## Table of Contents

- [Overview](#overview)

### What is Xata?

[Xata](https://xata.io) is a database platform built on PostgreSQL that allows teams to use Postgres at Scale:

- **Vanilla PostgreSQL** with automatic scaling and bottomless storage
- **Zero-downtime migrations** with pgroll
- **Instant branch-based development** workflows

### Examples

| Action                                     | URL                                                           |
| ------------------------------------------ | ------------------------------------------------------------- |
| Nightly Clone with PII removed             | [clone.yaml](./.github/workflows/clone.yaml)                  |
| Create a Xata database branch in every PR  | [pr-branch](./.github/workflows/pr-branch.yaml)               |
| Delete Xata database branch when PR closes | [delete-pr-branch](./.github/workflows/delete-pr-branch.yaml) |
