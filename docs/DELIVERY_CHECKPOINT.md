# Delivery checkpoint

Open AI agent: Coordinator — verified recovery snapshot, 2026-10-05.

Read the latest [fork delivery epic](https://github.com/fmarslan/YouthOpp-.github/issues/2), PRs, Actions and this file before resuming. Do not duplicate existing work.

## Authorized scope

Work only in `fmarslan/YouthOpp-.github`, `fmarslan/YouthOpp-data-pipeline` and `fmarslan/YouthOpp-youthopp.github.io`. Never send upstream PRs. The owner authorized branch work, task commits, reviewed single consolidated commit PRs into fork main and their merge. Comments, PRs and commit messages start `Open AI agent:`. Product, architecture, research, frontend, pipeline and independent QA roles are coordinated separately.

The owner explicitly approved cloud-browser Pages activation with “Yes”. Approval is granted; the current blocker is tool availability. No desktop actions were performed.

## Merged and verified

- Organization PR #4: English nonprofit-purpose mission/profile, contribution policies, AI governance and practical youth learning goals.
- Pipeline PRs #3–#7: durable collection, runner portability, immutable manifests, bounded release retention, source evidence and reviewed Czech programme metadata.
- Website PRs #4–#8: English static catalog, category/country pagination, attribution, source health, contributor scoring, Docs, accessibility checks, SEO/social discovery and accurate programme/institutional-grant labels.
- [Pipeline production run 37259905391](https://github.com/fmarslan/YouthOpp-data-pipeline/actions/runs/37259905391) succeeded on 2026-10-05, with 19 tests, prior-state restore, collection, manifest publication and retention. [Immutable release catalog-37259905391-1](https://github.com/fmarslan/YouthOpp-data-pipeline/releases/tag/catalog-37259905391-1) contains 32 records: 30 feed records and two reviewed Czech programme/institutional-grant metadata entries. Their application availability remains unknown.
- Website PR #8 hosted CI passed. Independent local QA recorded 75 generated HTML routes without link/metadata failures and 18 desktop/mobile route checks without reported failures; 12 website tests passed.
- [Website main run 37260144084](https://github.com/fmarslan/YouthOpp-youthopp.github.io/actions/runs/37260144084) passed tests, immutable release download, contributor refresh, production generation and artifact upload. Deployment failed at Configure GitHub Pages with `HttpError: Not Found`; deployment was skipped. A successful build is not a live rollout.

## Exact remaining blocker

GitHub Pages publishing must be enabled with GitHub Actions as the source in the [fork Pages settings](https://github.com/fmarslan/YouthOpp-youthopp.github.io/settings/pages). The connector does not expose that settings write. Two approved cloud-browser requests timed out without returning usable UI state; no settings change was verified.

A fresh HTTP probe at 2026-10-05 03:35 UTC found `https://fmarslan.github.io/YouthOpp-youthopp.github.io/` redirecting to `https://fmarslan.com/YouthOpp-youthopp.github.io/`, with final HTTP 404 and noindex. The owner's custom-domain routing needs verification after Pages activation. No working hosted catalog is claimed.

## Transparent constraints

The register has 110 candidates and 94 recent dated/cycle editorial evidence records, with at least three editorial publishers in all 28 target countries. Closed annual calls are included in that editorial metric. It does not establish three currently open calls or three reviewed automated integrations per country. All 28 countries retain the automated-coverage gap.

Czech metadata indexing uses two exact reviewed URLs, excludes article prose/images and preserves unknown deadline, destination and eligibility. Access-policy inspection is not an express reuse licence or publisher endorsement. NL/PT feed ingestion remains disabled because reviewed items did not provide qualifying calls. Further programme-page adapters need concrete relevance, access and technical review.

Optional Google/Bing verification and analytics remain disabled without owner-controlled identifiers. Six-hour collection and site cron definitions are active, but a scheduled event has not been independently observed. Passing push runs do not establish scheduler execution.

## Resume after Pages activation

1. Inspect current main, PRs and Actions; no duplicate PRs.
2. Enable Pages with GitHub Actions, rerun failed deployment, then inspect actual final host.
3. Correct SITE_URL/canonical/sitemap/social origin if needed without changing unrelated account routing.
4. Independently test hosted catalog, filters, pagination, Docs, sources, contributors, mobile/keyboard access and metadata.
5. Record hosted evidence and close delivery/QA only after rollout acceptance. Research/access limitations remain explicit backlog.

The continuation reminder was already disabled when inspected. This run did not re-enable it or create another automation. Remaining work is blocked on Pages settings access and final-host verification; completion is not claimed.
