# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Release Manager Responsibilities
The Release Manager owns the end-to-end release process for each release cycle.

### Scheduling
- Publish and maintain the release calendar at least two sprints in advance
- Confirm deployment windows with infrastructure and on-call teams
- Communicate schedule changes to all affected stakeholders promptly

### Communication
- Send a pre-release announcement (at least 24 hours before deployment) to stakeholders and support teams
- Issue a go/no-go confirmation to the delivery team before deployment begins
- Distribute post-release summary including changes shipped, any incidents, and follow-up actions

### Release Manager Checklist
- [ ] Release date confirmed with PM, QA, and engineering leads
- [ ] Deployment window reserved and on-call team notified
- [ ] Go/no-go criteria defined and agreed with stakeholders
- [ ] Pre-release announcement sent to stakeholders
- [ ] All pre-release requirements verified (see below)
- [ ] Release notes reviewed and approved by Technical Writer and PM
- [ ] Go/no-go decision made and communicated
- [ ] Post-release summary distributed within 24 hours of deployment

---

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Technical Writer: Documentation Checklist
Use this checklist to ensure documentation is complete and accurate for each release.

- [ ] Release notes drafted using the template above
- [ ] Release notes reviewed by PM and Release Manager
- [ ] User-facing documentation updated for all new or changed features
- [ ] API reference or runbook updated where applicable
- [ ] Internal documentation (runbooks, onboarding guides) reviewed for accuracy
- [ ] All documentation changes peer-reviewed by a subject-matter expert
- [ ] Documentation published or merged before release announcement
