# Delivery checkpoint

Open AI agent: Product Owner — recovery snapshot, 2026-10-05. Read current authorized fork main branches, issues, PRs and Actions before acting; live state supersedes this dated snapshot.

## Project identity and authorized operations

Public project references use [YouthOpp/.github](https://github.com/YouthOpp/.github), [YouthOpp/data-pipeline](https://github.com/YouthOpp/data-pipeline) and [YouthOpp/youthopp.github.io](https://github.com/YouthOpp/youthopp.github.io). These are canonical project identities, not claims that recorded fork runs executed upstream.

Implementation work is restricted to `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`. Never send upstream PRs. The owner authorized branches, per-task commits, reviewed single-consolidated-commit PRs into fork main and their merge. Comments, PRs and commits begin `Open AI agent:`. Coordinate separate Product Owner, Architect, Researcher, Frontend, Pipeline and independent QA roles; inspect current task owners before duplicating work.

Runtime download and publishing configurations must continue to point to the actual authorized execution repositories. Keep operational run/release/PR links truthful rather than replacing their owner with a canonical project name.

## Latest owner requirements

- The pipeline owns all adapters, collection Actions/scripts, datasets, data formats and source registry work.
- The website consumes validated pipeline outputs and presents them. Remove obsolete website datasets, duplicate registries and inactive collection logic after checking references.
- Clean both repositories of unused files, methods, scripts and invalid or obsolete data. Preserve active runtime/build inputs and ensure existing records match the agreed format and UI contract.
- Public README/profile and rendered Docs use canonical YouthOpp repository names and URLs.
- Keep the continuation reminder enabled until the owner explicitly requests disabling it. Completion, source failures and owner-dependent blockers do not supersede this instruction. The continuation reminder was checked and restored to enabled on 2026-10-05 at 09:23:22 UTC; keep this owner instruction authoritative. The prior 08:34:54 UTC restoration remains historical evidence. Older pause/disable instructions are superseded.

## Completed implementation and cleanup stage — 2026-10-05

English nonprofit-purpose mission/profile, AI-led governance, practical youth learning goals and community policies are merged. Legal charitable status and publisher endorsement are not claimed. The website implements a compact static catalog, category/country pagination, attribution and source health, contributor scoring, public Docs, accessibility features and discovery metadata.

Organization PR #12 merged at `b6519d926beeffaa4ab14a3d3be46c591af5996d`, establishing canonical public identities, repository responsibilities and owner-only reminder control. Pipeline cleanup PR #24 merged at `a7c7a9336e39a065055bc013b37c55c3ae611cc2`; website cleanup PR #18 merged at `4900ba8f79c36c647994dd175bebff8ffc89b6bc`. Independent remote-blob verification and relevant CI passed, with 50 pipeline and 18 website tests. Superseded pipeline research PR #21 was closed after consolidation; do not recreate it.

The pipeline removed inactive scripts and obsolete tracked snapshots, owns contributor-history collection alongside adapters/registry/data, and publishes `contributors.json` with catalog/report in the same SHA256/byte-size integrity manifest. The website removed unused source-data folders and collection code; it downloads validated pipeline catalog/contributor outputs and renders them. Legacy two-asset manifests remain readable for catalog restoration; a consumer using contributor assets requires a compatible release when rolling back.

Actual fork producer run `37282628375` published immutable release `catalog-37282628375-1` on 2026-10-05 at 08:17:06 UTC. Independent release/manifest/artifact checks verified 40 retained records, eight configured integrations and seven healthy collections. The Czech collection failed transiently; two last-successful records were retained with their prior freshness evidence. Luxembourg is present in this produced release rather than counted solely from its earlier merge.

Actual fork consumer run `37282968750` passed 18 tests, verified the exact catalog and contributor assets from that same immutable release, generated 40 records and completed custom deployment at 08:20:25 UTC. Independent exact-consumer artifact QA passed all 86 routes, catalog pagination of 30 plus 10 records, all links and three real contributor profiles. These generated-route checks remain distinct from live-hosted acceptance. A later dynamic Jekyll publisher, run `37282968337`, deployed to the same host at 08:20:36 UTC: the publisher conflict persists despite successful consumer execution. Its artifact `11333375041` differs from the custom artifact `11332739628` and was deployed eleven seconds later.

## OeAD programme metadata and measured producer — 2026-10-05 08:45 UTC

Pipeline PR #25 merged at `0659c373fa9639f0ca061bede157b1da0e62ba81` after 54 tests, hosted CI and independent review. Website copyright/attribution PR #19 merged at `4789af490b006caaf441ed4369b923a741040125`; its first successful custom consumer `37284218363` deployed at 08:32:29 UTC using the preceding 40-record release, with 87 artifact routes and the OeAD access/credit contract. Dynamic Jekyll run `37284217876` deployed fourteen seconds later at 08:32:43 UTC; no public overwrite resolution is claimed.

Actual fork producer `37284398143` published immutable `catalog-37284398143-1` at 08:34:20 UTC with 42 retained records and all nine configured integrations healthy. Independent production QA verified all assets and the canonical contracts: 110 research candidates, 111 embedded registry rows, exact OeAD title/link and required literal copyright attribution. Programme metadata retains unknown application dates/state/eligibility rather than implying an open call.

| Produced asset | Bytes | SHA256 |
| --- | ---: | --- |
| `catalog.json` | 345,116 | `339515208c4b3f7b8abcc68f4b018e3dbbfb2aa1be33d07294e8e77697b537e4` |
| `collection-report.json` | 11,865 | `8425e22b7935d8c0299e5536a243bb3c1ba32959b9a628a10d2db43e7a549f38` |
| `contributors.json` | 1,472 | `bed3a8ea05fd25709d09270a24d0a16b012697bc1121325734e15554e2f20b35` |

The complete contributor snapshot contains three attributed profiles and two unresolved commits; excluded automation and unknown identities do not gain invented human credit. Canonical project identities are separate from actual fork history inputs.

Consumer `37284218363`, attempt 2, passed 19 tests and successfully rebuilt job `111680885329` from the exact new 42-record release. Independent artifact QA passed 89 routes, OeAD copyright on associated catalog/source/detail pages, original attribution and unknown metadata semantics. Deploy job `111680966679` failed because attempts 1 and 2 published artifacts with the same `github-pages` name. This attempt remains a verified build/consumption result and a failed deployment; it was superseded by the measured repair below.

Website repair PR #20 merged at `1a6324547b428c2ca81372f483cbba873280d6f2` after independent exact-head review and CI `37285244079`. The five-line workflow correction assigns each build a distinct Pages artifact name and transfers that name to its deploy job.

Actual fork workflow `37285364296` validated the repair: attempt 1 selected `github-pages-1` and deployed at 08:43:28 UTC; full rerun attempt 2 consumed the exact same 345,116-byte catalog and 1,472-byte contributors from `catalog-37284398143-1`, selected `github-pages-2` despite two artifacts, and deployed at 08:44:42 UTC. A deploy-only attempt 3, job `111683553241`, retained the preceding build's artifact name `github-pages-2` and succeeded at 08:45:17 UTC. Independent actual artifact `11333288761` QA passed all 89 routes, 42 record detail pages, all four associated OeAD listing rows plus source/detail copyright, and three contributor profiles with two unresolved commits. These measured workflow reruns establish retry behavior, not live origin availability. On the repair push, dynamic publisher `37285363487` deployed at 08:43:41 UTC, thirteen seconds after the initial custom deployment; competing publication is still measured on a subsequent push.

A separate owner-private 42-record test publication succeeded natively at 08:38:37 UTC. No fresh hosted HTTP or browser-interaction acceptance is claimed. Private publication URLs, source identifiers, deployment IDs and access details are not republished here.

Both actual producer and consumer schedule events were separately observed in preceding stages. The current nine-source release supersedes earlier count/health snapshots without erasing the scheduled/outage evidence. Configured cron alone is not schedule acceptance; current push-run success is not a new schedule-event claim.

## Accepted dated country research and Spain renewal — 2026-10-05 09:22 UTC

Independent QA accepted the original three-to-five high-quality active research-source target where evidence permits: 94 sources have dated editorial evidence; 93 are eligible after excluding one co-published Croatian bilateral-call evidence entry. All 28 target country summaries retain at least three distinct editorial publishers. Inspection dates remain explicit: 99 registry rows retain 4 October dates and 11 have 5 October dates. This is acceptance of dated research evidence, not a fresh rights/current-call review of all 110 candidates, three automated adapters per country, or three currently open calls per country.

Pipeline research PR #27 merged at `a313ac4e44efd960f0593452cd4c80cccff90ab0`; website Docs PR #21 merged at `215a2bbd2e93f99be2056230f6a824115b7b4b0a`. Three existing Spain publishers were renewed with exact application/access evidence; no source or adapter was added. Fundación Carolina's annual windows are closed and permission is required. La Caixa's stage-specific Francesc Moragas research call is open on the review date until 7 October 2026 at 14:00 Spanish peninsula time, with the date independently corroborated by BOE; reuse permission remains required. INJUVE's indexed SEPI dates are not promoted to confirmed live availability because direct detail/legal/robots checks returned 502. Keep its collection gate closed; no failed fetch is treated as publisher inactivity.

Actual fork producer `37288808187` passed 54 tests and published `catalog-37288808187-1` at 09:15:45 UTC: 42 retained records, nine healthy integrations and 111 embedded registry rows, including the three exact renewed Spain rows. Independent manifest/release/artifact verification passed. Catalog: 346,514 bytes, SHA256 `097499e7ab749342d9d126ab423f92754b67b698b31fc2ae434c10dbc4025dd5`; contributors: 1,472 bytes, SHA256 `5acf353cafd298b6adebb29edae5234c47432dc5cb6f54ab485ddff4caef6cb3`.

Actual fork consumer `37289178982` passed 19 tests, verified those exact same assets and completed custom deployment at 09:19:36 UTC. Independent artifact `11335138370` QA passed 90 routes, 42 details and 1,843 internal link targets, including the newly published Spain Docs. The research registry remains 110 rows: 100 rights pending, six scoped metadata reviews, three permission-required and one reviewed manual-only. Current-call evidence is 22 national publishers across 20 target countries, plus one GLOBAL publisher; these counts and the nine integrations are separate transparency metrics, not additional country-research acceptance gates.

Pipeline issues #19 and #26 were closed as completed at 09:22:13 and 09:22:19 UTC after reviewed merges and exact downstream evidence. The broad delivery epic and website hosted QA remain open. Future freshness, access and permission reviews are maintenance/backlog work rather than an invented requirement to integrate every research candidate.

Dynamic publisher `37289177984` deployed different artifact `11335951471` at 09:19:49 UTC, thirteen seconds after the custom artifact. The latest public probe followed the inherited redirect and timed out with HTTP 000; this is inconclusive, not a fresh 404 or a live-availability acceptance. Earlier conclusive public 404 evidence remains dated. A separate owner-private test publication succeeded natively at 09:21:18 UTC with the reviewed Spain Docs and actual new input; no new hosted HTTP/browser acceptance is claimed, and no private identifiers or URLs are republished.

## Hosted acceptance and unresolved constraints

Successful collection, release, build, artifact upload and deployment remain separate from actual hosted acceptance. Historical checks are preserved in the Git and issue history; private deployment identifiers and access details are not republished here. Prior local desktop/mobile/keyboard and route checks do not establish current hosted behavior.

Public acceptance is still open. Two different Pages publishers previously deployed artifacts to the same host: custom website run 37271362237 at 06:14:17 UTC, then repository-root Jekyll run 37271362348 at 06:14:26 UTC. This is evidence of competing publication, not a direct settings read. The targeted owner/admin operation is Settings → Pages → Build and deployment → Source: GitHub Actions; rerun the custom workflow and verify a subsequent push has no competing dynamic publisher. The latest approved settings-page attempt reached a signed-out 404; no setting change was observed. Use the approved cloud-browser fallback only when available; do not repeat generic activation/login.

Inherited project-domain routing remains separately unaccepted: an independent public origin probe on 2026-10-05 at 08:22 UTC returned HTTP 404 after the cleanup custom consumer deployment. A public GET after the measured 08:45 UTC workflow repair also returned HTTP 404 at the inherited personal-project route. Earlier restricted-network 403 probes remain inconclusive. Publisher configuration and the inherited-domain owner decision are separate constraints. No personal website or DNS changes are authorized. Do not repeat or work around a previously rejected credential disclosure. Claim only hosted checks actually observed for their tested version.

The requested country target is three-to-five genuinely verified high-quality active research sources where evidence permits. It does not require three-to-five automated adapters or currently open calls per country. Dated research records identify at least three distinct recent editorial publishers in all 28 target countries; assess their evidence and inspection dates without implying every candidate has a fresh rights/current-call review. Research candidates, recent publication evidence, confirmed-open calls and automated integrations are different metrics. Programme/institutional metadata never establishes an open youth application; publisher geography never implies destination or eligibility. Keep missing dates, eligibility and application state unknown. Permission-required sources remain disabled; access restrictions and coverage gaps stay explicit. Optional owner-controlled search verification and analytics identifiers remain absent.

## Current independent work and recovery

The reviewed cleanup, OeAD metadata, retry repair and dated country-research stages are complete with measured producer/consumer evidence. Overall delivery remains open for actual hosted/public acceptance. Continue proportionate health checks and bounded freshness/permission maintenance from current state; do not reopen accepted country research solely because adapter totals or open-call counts are below three. Inspect exact current branch/issue/PR ownership before adding the next source or repeating completed stages. Carry validated pipeline Docs into the website through its normal consumption path rather than maintaining independent source copies.

After each completed stage, record the exact reviewed head, merged fork PR, relevant CI, producer release, verified consumer input and actual hosted evidence where available. Update this checkpoint from measured results. Keep delivery and public hosted QA open until acceptance passes. Continue feasible work when one task needs owner action; after completion perform lightweight health checks and report material changes only. Keep the reminder enabled unless the owner explicitly instructs otherwise.
