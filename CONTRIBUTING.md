# Contributing to ToxMCP

Thank you for helping improve the ToxMCP tools.

## Choose the owning repository

Open the issue or pull request in the repository that owns the affected tool. Use the [suite guide](https://github.com/ToxMCP/toxmcp) if you are unsure where a change belongs. For broad architecture or cross-repository proposals, begin with a discussion or issue before changing several repositories.

Repository-specific guidance takes precedence over this organization-wide default.

## Prepare a change

1. Work from the current default branch on a focused branch.
2. Keep the change small enough to review.
3. Add or update tests for behavior changes.
4. Update user-facing documentation and examples when interfaces change.
5. Run the repository's documented test, formatting, and security checks.
6. Explain the claim boundary: what the change supports and what it does not establish.

For scientific changes, identify data sources, versions, transformations, assumptions, uncertainty, applicability limits, and any required license or attribution. A passing test proves software behavior; it does not by itself prove scientific validity or regulatory readiness.

## Protect confidential information

Do not commit client data, unpublished study material, credentials, environment files, local machine paths, AI-agent session transcripts, prompts, local agent settings, or generated working artifacts. Use synthetic or openly redistributable fixtures and verify their terms before adding them.

Review AI-assisted changes as carefully as any other contribution. The contributor remains responsible for the code, evidence, licenses, and claims in the pull request.

## Pull requests

Describe the problem, the proposed change, verification performed, security and privacy impact, scientific impact, and any follow-up work. Link the relevant issue when one exists. Resolve review conversations and keep unrelated changes out of the pull request.

Report vulnerabilities through the private process in [SECURITY.md](SECURITY.md), not through an issue or ordinary pull request.
