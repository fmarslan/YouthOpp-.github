# Delivery checkpoint

AI Agent — Product Owner

This document supports recovery for the initial AI-led YouthOpp delivery. The working epic is [delivery coordination issue](https://github.com/fmarslan/YouthOpp-.github/issues/2); the product task is [governance task](https://github.com/fmarslan/YouthOpp-.github/issues/3).

## Agreed scope

Update organisation profile/governance, pipeline/adapters/source research, and the English website/catalog/docs/contributors/SEO. Independent Product Owner, Architect, Researcher, Developer and QA roles are coordinated by the root agent. Evidence and limitations must remain public and truthful.

## Delivery model

Use task branches and granular fork commits with `Open AI agent:` message prefix. Deliver one consolidated single-commit PR per repository targeting its fmarslan fork main branch. PRs contain an AI role prefix, concise change summary and observed validation; PRs need no issue links. The owner explicitly authorised reviewed fork PRs to be merged. Do not create YouthOpp upstream PRs.

## Recovery procedure

1. Read the epic, task issues and current repository state.
2. Inspect actual branches, commits and open PRs; do not assume prior work was pushed.
3. Identify unfinished tasks and resume specialist agents without duplicating completed work.
4. Run relevant validation and independent QA, fix findings, then assemble delivery branches.
5. Post final evidence and disable the recovery reminder when all agreed deliverables are complete.

## Product Owner checkpoint — 2026-10-04

Organisation mission, community policies, AI governance and product contract have local task commits. Seven internal links and whitespace checks passed. The website includes public governance, mission/product, accessibility and data-quality docs. Five website tests and a 20-record static build passed; QA additionally inspected desktop/mobile Chromium rendering and JavaScript-disabled routes. Consult issue comments for later evidence rather than treating this snapshot as a live status feed.

The coordinator reports three active integrated feeds and 89 researched source candidates spanning the EU's 27 member countries and the USA. Candidate coverage does not mean all candidates have proven recent activity, safe automated access or implemented adapters. Country-level quality verification remains in progress. The RSS adapter's destination countries, eligible countries and deadlines remain unknown; richer targeting cannot be claimed.

Fork work and concrete consolidated delivery branches have been prepared remotely by the coordinator. Earlier upstream PR creation returned `403 — Resource not accessible by integration`. The owner has since removed upstream delivery from scope: development, issues, PRs, merges and operations now target the fmarslan forks. Upstream permissions are no longer a delivery blocker. Prepared branches alone are not evidence of completed merge or deployment. The epic must remain open while delivery, research verification or rollout checks remain incomplete.

## Exact next actions

1. Complete per-country source verification and record evidence or explicit gaps in the source register.
2. Inspect fork PRs and prepared branches; create or update consolidated PRs against the corresponding fmarslan fork main branch. Do not rebuild duplicate branches before checking current state.
3. Inspect the remote delivery branches, confirm one commit per fork delivery PR, and rerun changed-file validation if additional research is integrated.
4. Review checks and merge the owner-authorised fork PRs, then configure fork Actions publication permissions and GitHub Pages deployment, run collection to produce the durable catalog release, and confirm the website retrieves that release and publishes correctly.
5. Supply optional Google/Bing verification and analytics configuration only from owner-controlled accounts; absent values remain disabled.
6. Record hosted smoke-test evidence before declaring rollout complete. Disable the recovery reminder only after the agreed work has actually completed.

Central fork issues are available; use them for roles whose other fork issue features remain disabled. This checkpoint records blockers honestly and does not assert that fork merges or production deployment succeeded.
