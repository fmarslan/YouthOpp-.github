# Delivery checkpoint

Open AI agent: Coordinator — recovery snapshot, 2026-10-04.

The coordination record is [fork epic #2](https://github.com/fmarslan/YouthOpp-.github/issues/2). Read current issue comments, PRs and Actions before resuming; this file is a dated snapshot.

## Authorized scope and delivery

Work only in `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`. Never create YouthOpp upstream PRs. Task branches retain per-task commits; reviewed delivery PRs contain one consolidated commit into the corresponding fork main. The owner explicitly authorized their merge. New comments, PR descriptions and commit messages begin `Open AI agent:`.

The coordinator operates Product Owner, Architect, Researcher, Frontend, Pipeline and independent QA agents. Do not duplicate completed work. User desktop access is outside this cloud workflow.

## Verified completed stages

- Organization PR #4 merged: English mission, profile, contribution policies, AI governance and practical youth learning goals.
- Pipeline PR #3 and portability correction #4 merged. Main run [37230560927](https://github.com/fmarslan/YouthOpp-data-pipeline/actions/runs/37230560927) passed and published [catalog-37230560927-1](https://github.com/fmarslan/YouthOpp-data-pipeline/releases/tag/catalog-37230560927-1) on 2026-10-04 at 20:02:44 UTC: 30 records from three successful feeds. A successful versioned release is evidence of data publication, not website deployment.
- Website PR #4 and documentation correction #5 merged. Production run [37230774766](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37230774766) passed tests, catalog download, contributor refresh, static generation and artifact upload. Six website and nine pipeline tests plus prior independent local desktop/mobile/static-route audits passed.
- Fork issue bodies now reflect authorized fork-main merges and the required attribution prefix.

## Current blockers and limitations

The production deploy job failed at `actions/configure-pages@v5`: `Get Pages site failed` / `HttpError: Not Found`. Repository Pages publishing must be enabled with GitHub Actions as source. The connector exposes no Pages settings write; cloud-browser fallback approval was requested previously and has not been granted in the visible conversation. Do not assume broad repository merge authorization grants that pending browser permission.

Independent HTTP QA on 2026-10-04 found `https://fmarslan.github.io/YouthOpp-youthopp.github.io/` redirects to `https://fmarslan.com/YouthOpp-youthopp.github.io/`, which returns 404. Confirm the actual final hosted URL and canonical/sitemap origin after activation. Do not report the catalog/site as live based on local tests or successful artifact generation.

The baseline source register has 89 candidates, 58 with recent opportunity-publication evidence. Seven of 28 target countries meet three distinct recent publishers; 21 coverage gaps remain. Candidates, recent publication evidence, currently open calls and reviewed automated integrations are separate facts. Three feeds are integrated; publisher rights and other automation statuses remain explicitly documented. Country/deadline/eligibility metadata stays unknown when absent. Optional Google/Bing verification and analytics require owner-controlled identifiers and remain disabled when absent.

## In-progress independent work

The current run is integrating verified additional national-publisher evidence, digest verification and bounded versioned-release retention, and accurate Organization/BreadcrumbList discovery metadata. Consult specialist issue comments and forthcoming fork PRs before recreating branches. Source research owns pipeline registry/docs; the coordinator copies their validated equivalents to website data/docs. Root owns this checkpoint.

## Recovery and acceptance

1. Read the fork epic, research and QA issues, current main branches, existing PRs and Actions. Inspect unfinished work before spawning specialists.
2. Finish independent authorized work, document evidence/gaps, run focused checks and independent QA, then review/merge one-commit fork-main delivery PRs. Never send upstream PRs.
3. Once Pages is enabled, rerun the failed main deployment, inspect actual deployed routes on the final host, including mobile/keyboard use, source/docs/contributor routes, canonical URLs, filters and pagination.
4. Record each completed stage and exact remaining blocker in this file and fork issues. Keep the delivery epic and hosted QA open until actual rollout is verified.
5. Stop the recovery reminder after all feasible work is finished or when fully blocked on required owner action; record that reason. A later resumed run must still inspect durable GitHub state.
