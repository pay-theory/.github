## Type
<!-- Tick one. -->
- [ ] Feature / bug → premain
- [ ] Hotfix → main (`type:hotfix`)
- [ ] Promotion premain → main
- [ ] Back-merge main → premain

## Change
<!-- What changed and why. Every PR needs a Linear ticket. -->
Linear: PRD-

## Security impact
<!-- Never paste card data, secrets or tokens here. Tick all that apply. -->
- [ ] Touches card data, keys, tokens or authentication
- [ ] Changes infrastructure, IAM, network or CI/CD
- [ ] Adds or updates dependencies
- [ ] Changes what gets logged or stored
- [ ] None of the above

If any box above is ticked, describe the risk and how it's handled:

## Secure coding (PCI 6.2.4)
- [ ] Inputs validated; no new injection surface (SQL, GraphQL, command)
- [ ] Authentication and authorization checked on new or changed endpoints
- [ ] No card data, secrets or tokens logged or stored
- [ ] Errors don't leak internal details
- [ ] N/A: no runtime code change (docs, tests or config only)

## Significant change (PCI 6.5.2)
<!-- Yes if this adds or changes a system, network path, auth flow or data store in the cardholder data environment. A yes means PCI controls get re-confirmed after deploy. -->
- [ ] No
- [ ] Yes, because:

## Testing
<!-- What you ran and where (unit, integration, lab/QA stage). Link results. -->

## Rollback
<!-- How to undo this: revert the PR, redeploy the previous build, data or migration steps. -->

## Approvals
<!-- The reviewer must not have commits in this PR. Code owners are requested automatically. -->
- [ ] Reviewed by someone with no commits in this PR
- [ ] Release approver sign-off (promotions and hotfixes only)
