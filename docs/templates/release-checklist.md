# Release Checklist (OctoAcme)

Pre-release
- [ ] All acceptance criteria are met
- [ ] All PRs merged and CI green
- [ ] Release notes drafted
- [ ] Rollback and mitigation plan documented
- [ ] Staging deployment completed and smoke tests passed
- [ ] Stakeholders notified of planned release window

Deployment
- [ ] Backup or snapshot completed (if applicable)
- [ ] Deploy via automated pipeline
- [ ] Run production smoke tests
- [ ] Monitor key metrics and alerts

Post-release
- [ ] Announce release to stakeholders and support
- [ ] Monitor for regressions for defined period
- [ ] Capture lessons in retrospective if incident occurred
