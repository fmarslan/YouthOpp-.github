# Delivery checkpoint

Open AI agent: Coordinator — verified recovery snapshot, 2026-10-05 04:33 UTC.

Read the current [fork delivery epic #2](https://github.com/fmarslan/YouthOpp-.github/issues/2), task issues, PRs and Actions before acting. This is a dated recovery record; live GitHub state is authoritative.

## Authorized scope

Work only in `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`. Never send YouthOpp upstream PRs. The owner authorized branches, task commits, reviewed single-commit PRs into fork main and their merge. New agent comments, PRs and commit messages start `Open AI agent:`.

The owner explicitly approved cloud-browser Pages activation. No desktop action is authorized or required.

## Completed and merged

- Organization PRs #4–#7: English nonprofit-purpose mission/profile, contribution policies, AI governance, youth learning goals and delivery evidence.
- Pipeline PRs #3–#8: durable collection, runner portability, immutable manifests, bounded retention, 110-source evidence, reviewed Czech metadata and the final US/BG/CY evidence reconciliation.
- Website PRs #4–#9: English static catalog, category/country pagination, source attribution/health, contributor scoring, all public Docs, accessibility/discovery metadata, programme labels and byte-identical final research evidence.
- Completed task issues: organization architecture #1, pipeline research #1, pipeline implementation #2 and website contributor history #1. Delivery epic #2 and website delivery/hosted QA #2–#3 remain open.

[Pipeline main run 37263518031](https://github.com/fmarslan/YouthOpp-data-pipeline/actions/runs/37263518031) passed validation/tests, prior-state restore, collection, versioned manifest publication and retention. [Release catalog-37263518031-1](https://github.com/fmarslan/YouthOpp-data-pipeline/releases/tag/catalog-37263518031-1) contains 32 records from four healthy sources. Two Czech records are reviewed programme/institutional metadata; application availability remains unknown.

[Website PR #9 CI 37263837162](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37263837162) passed. [Website main run 37263870473](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37263870473) passed 12 tests, versioned release download, contributor refresh, 32-record production build and Pages artifact upload. Deployment failed at Configure GitHub Pages; Deploy GitHub Pages was skipped. Successful build/upload is not live deployment.

Independent QA reproduced 19/19 pipeline tests and 12/12 website tests, verified the release asset digest, 75 generated HTML routes, metadata/internal links and desktop/mobile checks. No Pages-independent code defect is currently known.

## Exact hosted blocker

Repository API reports `has_pages:false`. GitHub Pages must be enabled with **GitHub Actions** as the publishing source in the [fork Pages settings](https://github.com/fmarslan/YouthOpp-youthopp.github.io/settings/pages). The connector has no Pages/administration write operation. `actions/configure-pages` cannot self-enable Pages with the normal `GITHUB_TOKEN`; doing so requires a separate owner/admin token, which the project does not request or store.

The approved cloud browser now reaches GitHub, but its session is signed out. GitHub presents username/password, Google, Apple and passkey methods; secure policy requires the owner to choose and complete authentication. No credentials were requested in chat and no login method was selected on the owner's behalf.

Fresh QA found the GitHub project URL redirecting to `https://fmarslan.com/YouthOpp-youthopp.github.io/`, where root, opportunities, Docs and contributors routes return 404. After Pages activation, verify the final custom-domain routing. If that is the intended public base, set `SITE_URL=https://fmarslan.com/YouthOpp-youthopp.github.io` before the final production build so canonical, sitemap, OpenGraph and JSON-LD use the final origin.

## Research and operational constraints

The register contains 110 candidates. All 28 target countries have at least three distinct publishers with recent editorial evidence, including closed annual programmes. This does not establish three currently open publishers or three automated/permission-reviewed adapters per country.

After final reconciliation, 19 publishers across 17 countries have explicitly confirmed open evidence; no country has three. Only four sources are operational. Rights/access review remains pending for most candidates; ordinary RSS/robots access is not a reuse licence. The Czech metadata adapter publishes only original title/link/date for two exact reviewed URLs and does not infer deadline, destination or eligibility.

The US Fulbright 2027/28 competition is recorded as open through 2026-10-06 17:00 ET, with earlier institutional deadlines possible. Time-limited state requires later maintenance.

Both workflows contain active six-hour cron definitions: pipeline at minute 17 and website at minute 25 UTC. No `schedule` event has yet been observed. The current pipeline workflow entered main after the 00:17 window; the next expected window is 06:17 UTC, followed by the site at 06:25 UTC. Cron configuration or push success alone is not measured schedule execution.

Optional Google/Bing verification and analytics remain disabled until owner-controlled identifiers are supplied.

## Resume actions

1. Inspect main, open PRs/issues, Actions and this checkpoint; do not duplicate completed work.
2. Complete GitHub authentication in the approved cloud-browser handoff and enable Pages with GitHub Actions.
3. Rerun/dispatch current website main; require a successful deploy job and actual environment URL.
4. Confirm the final public base, then set `SITE_URL` only if needed and rerun.
5. Independently verify live root/catalog/source/Docs/contributor/detail/pagination routes, assets, canonical/OG/JSON-LD/sitemap/robots/llms, mobile layout and keyboard behavior.
6. Observe at least one real `schedule` run for pipeline and website. Keep scheduled-run absence separate from code failure.
7. Close website QA/delivery and epic only after hosted acceptance. Disable the recovery reminder when live and scheduled acceptance are complete, or if the task is explicitly paused because owner authentication remains unavailable.
