# Delivery checkpoint

AI Agent — Product Owner

This document supports recovery for the initial AI-led YouthOpp delivery. The working epic is [delivery coordination issue](https://github.com/fmarslan/YouthOpp-.github/issues/2); the product task is [governance task](https://github.com/fmarslan/YouthOpp-.github/issues/3).

## Agreed scope

Update organisation profile/governance, pipeline/adapters/source research, and the English website/catalog/docs/contributors/SEO. Independent Product Owner, Architect, Researcher, Developer and QA roles are coordinated by the root agent. Evidence and limitations must remain public and truthful.

## Delivery model

Use task branches and granular fork commits with `Open AI agent:` message prefix. Deliver one consolidated single-commit upstream PR per repository. PRs contain an AI role prefix, concise change summary and observed validation; upstream PRs need no issue links. Do not merge PRs automatically.

## Recovery procedure

1. Read the epic, task issues and current repository state.
2. Inspect actual branches, commits and open PRs; do not assume prior work was pushed.
3. Identify unfinished tasks and resume specialist agents without duplicating completed work.
4. Run relevant validation and independent QA, fix findings, then assemble delivery branches.
5. Post final evidence and disable the recovery reminder when all agreed deliverables are complete.

## Product Owner checkpoint

Branch: `task/product-governance`. Organisation profile, contribution policy, community conduct, AI governance and product contract drafted. Internal-link and whitespace checks are required before committing. A successful local commit is not evidence of a published upstream change.

Issues were initially disabled on forks; central organisation fork issues subsequently became available. Continue using central fork issues for roles whose repository issue feature remains disabled.
