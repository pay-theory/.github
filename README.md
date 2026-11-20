# pay-theory/.github

Org-wide defaults for every pay-theory repository.

- `.github/pull_request_template.md`: the default PR description (PCI DSS 6.5.1 change record). A repo with its own template overrides it.
- `.github/workflows/pr-body-check.yml`: run on every PR by the "PCI change control" org rulesets. It fails when the PR description has no type ticked, no Linear ticket, or no answer to the 6.5.2 significant-change question.

Changes here affect every repo. Open a PR; it needs a non-author approval. Tracked in Linear PRD-840 and PRD-839.
