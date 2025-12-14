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
- Quality Assurance Lead sign-off on release readiness
- Release notes drafted (coordinated by Project Manager)
- Rollback / mitigation plan documented
- Smoke tests prepared and validated
- Data migration validated by Data Steward (if applicable)
- Change management and user communications ready (Change Manager)
- Stakeholders notified of release timing (Stakeholder Engagement Lead)
- Project Sponsor approval for major releases

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (Quality Assurance Lead validates)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Stakeholder Engagement Lead coordinates)
- [ ] Change Manager confirms user communications sent
- [ ] Monitor adoption and feedback (Change Manager and Product Manager)

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
