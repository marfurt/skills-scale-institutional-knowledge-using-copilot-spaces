# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- QA Lead has reviewed test results and provided release readiness sign-off
- Passing CI and security scans
- Release notes drafted (Tech Writer review recommended)
- Rollback / mitigation plan documented and reviewed by DevOps Engineer
- Smoke tests prepared and validated by QA Lead

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] QA Lead release readiness sign-off obtained
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] DevOps Engineer confirms pipeline and environment readiness
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Tech Writer publishes or updates release notes
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
