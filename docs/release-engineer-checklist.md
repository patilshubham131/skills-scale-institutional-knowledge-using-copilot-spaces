# Release Engineer — Deployment Checklist

Purpose: standard checklist for staging and production releases to ensure consistency and reduce risk.

Pre-release
- [ ] All PRs merged for this release and linked to release notes
- [ ] CI pipeline green (unit, integration, security scans)
- [ ] Migration scripts reviewed and staged in a non-production environment
- [ ] Release window communicated to stakeholders and support

Staging
- [ ] Deploy to staging using automated pipeline
- [ ] Run automated and manual smoke tests
- [ ] Validate metrics and logs for regressions
- [ ] Sign-off from QA and Release Engineer

Production
- [ ] Schedule production deploy in pipeline and notify on-call
- [ ] Take backup/snapshot if applicable
- [ ] Deploy to production with gradual rollout (canary/percentage-based)
- [ ] Run post-deploy smoke tests and sanity checks
- [ ] Monitor key metrics and error budgets for 30–60 minutes
- [ ] Confirm success and announce release completion

Rollback / Incident
- [ ] Pre-approved rollback plan available
- [ ] If rollback required, execute and validate restored state
- [ ] File incident report and capture action items

Notes
- Owner: Release Engineer (primary), Project Manager (coordinator)
- Add release-specific steps to the release notes or runbook as needed.
