# Delivery checkpoint

Open AI agent: Coordinator — recovery snapshot, 2026-10-05. Live fork state is authoritative; read current issues, PRs and Actions before acting.

## Authorized scope

Work only in `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`; never send upstream PRs. The owner authorized branches, per-task commits, reviewed consolidated single-commit PRs into fork main and merge. Comments, PRs and commits begin `Open AI agent:`. Coordinate Product Owner, Architect, Researcher, Frontend, Pipeline and independent QA. Browser permission already granted; no desktop work.

## Completed stages

Organization PRs #4–#8 deliver English nonprofit-purpose mission/profile, AI governance, youth learning goals, contribution policies and checkpoints. Legal nonprofit status or publisher endorsement is not claimed.

Pipeline PRs #3–#11 deliver durable collection, immutable integrity manifests, bounded retention, source research, reviewed Czech and NASA metadata, and canonical source/category/record-kind taxonomy. Main `d14163603288cabe40b90d728623364441e36dfa` passes 36 tests. Website PRs #4–#13 deliver English compact directory, static category/country pagination, source attribution/health, contributors, Docs, accessibility and discovery metadata. PR #13 is merged at `d51e75bb598d55bd50d20783d9c9ef617a77c5b5`: canonical record-kind actions and source/model Docs are verified by 17 tests for both project-path and root hosting. Main run [37269252581](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37269252581) succeeded after merge.

The compact interface separates source capability from record classification. Explicit adapter IDs join research to runtime health. Multi-category memberships preserve one canonical record. Search applies only to the current page, as disclosed. Publisher geography does not imply host country or eligibility; missing values remain unknown.

## Measured production evidence

First actual producer `schedule` run [37269037131](https://github.com/fmarslan/YouthOpp-data-pipeline/actions/runs/37269037131), created 2026-10-05 05:43:24 UTC, completed successfully. [Release catalog-37269037131-1](https://github.com/fmarslan/YouthOpp-data-pipeline/releases/tag/catalog-37269037131-1) contains 35 records from five integrated sources: OFY 12, OD 10, SC 10, Czech 2 and NASA 1. Catalog is 317,664 bytes, SHA256 `cf843cce251101d4fee45fb85061074994e705c08fd7ab2af2603913d9c459c1`.

Four source collections are healthy. The Czech fetch failed transiently in that run; its two previously reviewed records were retained, last successful collection 05:38:25 UTC. Failure is visible in collection health. Programme/institutional records do not establish open youth applications or infer deadlines/eligibility.

Website main run [37267728235](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37267728235) deployed successfully. Pages is enabled; earlier disabled/authentication blockers are superseded. Actual public acceptance remains incomplete: prior direct HTTP checks found the project URL redirecting to `https://fmarslan.com/YouthOpp-youthopp.github.io/` and returning 404. Fresh run probes received 403 in the restricted execution network, which is inconclusive about origin availability. Do not change the personal website or DNS without specific authorization. Subdomain/custom-domain configuration remains an owner decision.

Owner-private [test Site](https://youthopp-test.fmarslan.chatgpt.site) version 4 is successfully deployed from exact pushed source `e6e727ecf3bb1493b84565b4d3f67e1a3408b329`, with reviewed merged website code, the digest-verified 35-record scheduled release, full contributors and source/model Docs. Native deployment `appgdep_6ac33a6e8b188191a1269cf98f5b021e` succeeded at 2026-10-05 05:49:52 UTC. Fresh authenticated version 4 live HTTP QA returned 200 for all eight checked routes: root, opportunities, sources, Docs, contributors, data-model Docs, access-review Docs and sitemap. A private test Site does not satisfy public Pages acceptance.

## Remaining constraints and next actions

- PR #13 has merged with passing CI and successful main deploy. Verify exact hosted consumption and routes.
- The same owner-private test Site is refreshed and deployed, with eight hosted routes returning 200. Finish independent asset, record-kind, metadata and mobile/keyboard acceptance.
- Observe a real website `schedule` event separately from successful push builds. Producer scheduled execution is verified.
- Continue feasible permission/access-reviewed source work from current research state. The research register has 110 sources; the catalog embeds 111 registry rows, including one unmatched runtime aggregator; editorial publication evidence, confirmed-open calls and operational reviewed adapters are separate metrics. No country has three reviewed working adapters; document gaps without fabrication. IKY requires prior permission and remains disabled. NASA uses bounded factual programme metadata, not an inferred open call.
- Optional Google/Bing verification and analytics remain disabled without owner-controlled identifiers.
- Keep overall epic and hosted QA open until actual public/scheduled acceptance. Update this checkpoint after completed stages; disable recovery only after all feasible authorized work is complete or a non-transient owner action fully blocks it.

## Additional independently measured acceptance — 2026-10-05 06:00 UTC

Open AI agent: Independent recovery acceptance, preserving concurrent Portugal source work.

- Real consumer schedule run [37269677990](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37269677990), created 05:52:10 UTC, passed every build and deploy step. Its log verifies 317,664 bytes from immutable `catalog-37269037131-1`; both producer and consumer schedule events are now observed, superseding the earlier unobserved-consumer note.
- Independent local QA passed all 80 generated routes, metadata/link checks, responsive desktop/mobile and keyboard checks. Focused homepage/source-directory retests confirm 35 records, four healthy sources and one transient Czech fetch error; two prior Czech metadata records and prior success times remain intact. Transient source failure is not a reason to stop recovery.
- The exact private Site input catalog changed during source packaging. Its two affected rendered pages were rebuilt from the verified scheduled snapshot and retested, then pushed at `e76c67e97b1c61b219357c597f15cfda810093bf`. Native private deployment `appgdep_6ac33cd3c5908191991102dee67e8901`, saved version `appgprj_6ac32e65c6dc819189d370dea0372ae0~appgver_aa4ad2398fd881918d64b7de68958f73`, succeeded at 06:00:04 UTC at the same [test Site](https://youthopp-test.fmarslan.chatgpt.site), preserving owner-private access. This corrected rendering supersedes the prior source/deployment for current source-health display.
- Earlier separately recorded version-4 hosted HTTP evidence is preserved. This independent run could not perform authenticated live functional QA of the corrected version: automatic approval review rejected transmitting the private access bearer from a local secret file because explicit authorization for that credential disclosure was absent. No credential workaround was attempted. Native publication and local QA do not establish current hosted functional acceptance.
- Public Pages still lacks acceptance: independent direct probes after the merged main deployment followed the inherited `fmarslan.com/YouthOpp-youthopp.github.io/` route to 404; other restricted-network probes returned inconclusive 403. Owner-controlled custom-domain/routing configuration is required, with no personal-site or DNS edits authorized by this stage.
- README-only pipeline PR [#13](https://github.com/fmarslan/YouthOpp-data-pipeline/pull/13) is already merged with successful CI and independent review. Portugal metadata PR [#14](https://github.com/fmarslan/YouthOpp-data-pipeline/pull/14) remains separately owned and in progress; do not duplicate it or treat its unmerged adapter as deployed coverage. Keep recovery active while this feasible work remains. Keep overall and public hosted QA issues open.
