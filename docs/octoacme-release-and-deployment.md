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
- [ ] Complete handoff to Support Engineers using [Role Handoff Checklist](octoacme-role-handoff-checklist.md)
- [ ] Ensure DevOps monitoring and alerts are configured

## Role-Specific Responsibilities

**DevOps Engineer:**
- Execute deployment pipeline
- Monitor system health during deployment
- Maintain rollback capability
- Configure post-deployment monitoring

**QA Engineer:**
- Execute smoke tests in staging and production
- Verify critical user flows
- Document any issues found

**Support Engineer:**
- Review release notes and feature documentation
- Prepare knowledge base articles
- Monitor support channels post-release
- Escalate issues to appropriate teams

**Product Manager / Project Manager:**
- Approve go/no-go decision
- Coordinate stakeholder communication
- Track success metrics post-release

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

## Related Resources
- [Role Handoff Checklist](octoacme-role-handoff-checklist.md)
- [Cross-Role Interaction Scenarios](octoacme-cross-role-interaction-scenarios.md) - See "Scenario 6: Release Planning and Coordination"
