# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (PM)
- Passing CI and security scans (Security/Compliance Officer)
- Release notes drafted (Release Manager)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared (QA Lead)
- Customer communication plan ready (Customer Success Manager)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) (Release Manager)
- [ ] Backup or snapshot (if applicable) (Release Manager)
- [ ] Deploy to staging and run smoke tests (QA Lead)
- [ ] Deploy to production (automated pipeline preferred) (Release Manager)
- [ ] Run post-deploy verifications (QA Lead)
- [ ] Announce release to stakeholders and support (Release Manager, Customer Success Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager)
  - Rollback to last known-good release if necessary (Release Manager)
  - Triage root cause and capture action items (PM, Release Manager, QA Lead)
  - Communicate status to stakeholders (Release Manager, Customer Success Manager)
  - Document security implications if applicable (Security/Compliance Officer)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
