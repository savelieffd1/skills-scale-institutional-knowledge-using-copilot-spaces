# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (by Release Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Customer Success team briefed on changes and customer impact
- Support documentation updated if needed

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) and communicated by Release Manager
- [ ] Customer Success team notified of deployment timing
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (coordinated by Release Manager)
- [ ] Customer Success Manager notifies affected customers of changes

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Release Manager coordinates rollback communication
  - Rollback to last known-good release if necessary
  - Customer Success Manager communicates with affected customers
  - Triage root cause and capture action items
  - Post-incident blameless retrospective scheduled

See also: [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths.

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
