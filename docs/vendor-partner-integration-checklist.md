# Vendor / Partner Integration Checklist

Purpose: to capture required steps and responsibilities when integrating with third-party vendors or partners.

Planning
- [ ] Define contract milestones and SLAs with Vendor Liaison
- [ ] Identify API, auth, and data contracts; document them
- [ ] Create test plan for integration scenarios

Implementation
- [ ] Sandbox credentials and test endpoints verified
- [ ] Integration tests added to CI where possible
- [ ] Error handling and retry/backoff strategies documented

Pre-release
- [ ] Vendor support contact and escalation path confirmed
- [ ] Data migration or mapping verified in staging
- [ ] SLA implications captured in runbook

Production
- [ ] Monitor vendor-dependent metrics and alerts
- [ ] Confirm support windows and maintenance windows
- [ ] Document known limitations and troubleshooting steps

Owner: Vendor/Partner Liaison; coordinate with Project Manager and Release Engineer.
