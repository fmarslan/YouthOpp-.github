# Delivery checkpoint

Open AI agent: Coordinator — verified recovery snapshot, 2026-10-05.

Read [fork delivery epic #2](https://github.com/fmarslan/YouthOpp-.github/issues/2), current task issues, PRs and Actions before acting. This is a dated snapshot, not a substitute for live state.

## Scope and authorization

Work only in `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`. Never create YouthOpp upstream PRs. The owner authorized task branches and commits, reviewed one-consolidated-commit PRs into the corresponding fork main, and their merge. New comments, PR descriptions and commits begin `Open AI agent:`. Roles are Product Owner, Architect, Researcher, Frontend, Pipeline and independent QA; they share the connected account rather than separate GitHub identities. Work stays in the cloud; no user desktop access.

The user explicitly answered **Yes** to enabling GitHub Pages through the cloud browser. That permission persists. Do not ask for it again. Browser create-tab, state and reset operations each timed out at the tool connection; no Pages settings change is verified.

## Completed stages and observed evidence

- Organization mission/profile, community guidance, product contract and AI governance were delivered in fork PR #4; this update corrects the attribution policy and recovery state.
- Pipeline PRs #3–#7 are merged, including runner portability, verified immutable manifests, bounded release retention, country research and the exact-URL Czech metadata adapter. [Production run 37259905391](https://github.com/fmarslan/YouthOpp-data-pipeline/actions/runs/37259905391) passed all 19 tests, previous-state recovery, four source collections, manifest publication and newest-30 version retention.
- The actual immutable [catalog-37259905391-1 release](https://github.com/fmarslan/YouthOpp-data-pipeline/releases/tag/catalog-37259905391-1), published on 2026-10-05 at 03:34:17 UTC, has 32 records and four healthy sources. Independent QA downloaded 44,733 catalog bytes and verified SHA256 `41fa4b6a49f7246e1f2469b14c07470c8c7439929f718a3b96a6c884dcfba89d`.
- Exactly two Czech items retain original titles/links/dates, empty publisher-prose summaries, unknown availability, null deadlines and empty country eligibility. Programme overview and institutional grant are visibly distinct from open individual application calls. Eight unrelated feed news/alumni items are excluded; exhausted selection preserves prior metadata and success timestamps.
- Website PRs #4–#8 are merged: English catalog and Docs, contributor histories, fork project paths, immutable catalog verification, source-health labels/deduplication, discovery metadata, programme-kind notices and complete adapter evidence. [Main run 37260144084](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37260144084) passed 12 tests, verified the exact 44,733-byte immutable release, refreshed contributors, built 32 records and uploaded the Pages artifact. Its deployment failed separately.
- Independent QA passed 75 local HTML routes and 18 desktop/mobile route checks, with original-language titles, bounded pagination, keyboard skip links, truthful source health, escaped content and useful metadata. This is local implementation verification, not hosted acceptance or accessibility certification.
- Granular role commits are durable on `task/reviewed-programmes-20261005` and `task/programme-documentation-20261005`; corresponding merged delivery PRs each contain one consolidated commit.

## Source coverage and limits

The synchronized registry contains 110 unique candidates, 94 primary dated/cycle editorial evidence entries and 93 eligible evidence entries after excluding a duplicated co-published programme. Country counts deduplicate operators. All 28 target countries have at least three independent publishers with recent editorial activity; this includes closed annual rounds and institutional programmes.

No country yet has three independently classified confirmed-open publishers or three reviewed working automated adapters. Zero in those summaries means insufficient classified evidence, not proof that no open opportunities exist. Four sources are enabled: three global opportunity feeds and the narrowly selected Czech programme feed. Do not turn source geography into destination or applicant-country eligibility. Missing deadlines/eligibility remain unknown. NL/PT RSS stays disabled because the observed items supplied no selected opportunity calls; ordinary reserved copyright alone is not treated as an automatic indexing prohibition. Czech access-policy review permits the project's bounded metadata-only indexing model without claiming an express reuse licence, publisher approval or endorsement.

Optional Google/Bing verification and analytics require owner-controlled identifiers and remain disabled when absent. Nonprofit purpose is not registered charitable status; contribution scores are public activity indicators, not hiring or award guarantees.

## Exact deployment blocker

Main run 37260144084 failed at `actions/configure-pages@v5` with `Get Pages site failed` / `HttpError: Not Found`; deployment was skipped. Repository Pages must be enabled with GitHub Actions as publishing source. The connector has no Pages settings write capability. The approved cloud-browser fallback is currently unavailable because its tool calls time out, rather than because permission is missing.

Independent live HTTP probes on 2026-10-05 at 03:27 UTC still redirected `https://fmarslan.github.io/YouthOpp-youthopp.github.io/` to `https://fmarslan.com/YouthOpp-youthopp.github.io/`, returning 404; the direct opportunities route also returned 404. Check the actual final host and configure `SITE_URL` consistently after Pages activation. A successful build, upload or data release is not a live website.

Both production workflows previously reported `active` and contain six-hour schedules (pipeline minute 17, site minute 25). No completed scheduled trigger has yet been observed; do not claim measured schedule execution from cron configuration alone. Continue checking actual Actions events.

## Recovery actions

1. Inspect current fork main, existing task branches/PRs, source and QA issues. Reuse completed implementation; never duplicate merges or upstream PRs.
2. Continue feasible per-country source/access/adapter and explicit current-call verification. Validate deterministic selection, attribution, unknown metadata, safe fetching and outage preservation; publish updated evidence under site Docs. Do not treat editorial-count completion as automated-country coverage completion.
3. Retry the already approved cloud-browser connection at most once per run. If it becomes available, enable Pages, rerun failed main deployment and independently verify actual hosted catalog, Docs, contributor routes, canonical origin, mobile/keyboard behavior and pagination. If it times out, record the transient failure and proceed with independent work.
4. Keep the delivery epic and hosted QA open until live acceptance passes. Record exact completed stages and remaining constraints in issues and this checkpoint. The recovery reminder is active again after the user's browser approval; disable it only after all feasible authorized work is finished or when fully blocked on required owner action, not solely because this transient browser operation fails.
