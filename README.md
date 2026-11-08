# RepoAccord Sandbox

This repository is a disposable test bed for RepoAccord.
It is safe to break and is not a real project.

## Test stages

### Dry-run
Push to an allowed branch with dry-run enabled.
Check the plan and output without creating issues or pull requests.

### Live without branch protection
Use a test token and disable dry-run without branch protection.
Confirm issue and pull request creation and recovery behavior.

### Live with a required check
Require the CI check on the target branch and disable dry-run.
Confirm auto-merge is enabled only after the check is proven.
