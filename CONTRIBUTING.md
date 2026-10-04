# Contributing to YouthOpp

Help young people spend less time searching and more time understanding their opportunities. You can research a source, write an adapter, fix a link, improve accessibility, review a translation, document a decision or test a change. A first contribution can be small.

## Start with a task

Check the relevant repository for an existing task before opening one. Explain the problem, affected users, evidence and a clear acceptance criterion. Where issues are disabled, use the checked-in task register until a maintainer enables issues. Do not invent issue identifiers or claim a task has been posted when it has not.

Use a feature branch. Keep changes scoped, include relevant tests and explain what you verified. Maintainers review changes before merge. Development history can contain task commits; the current delivery policy consolidates each repository's release into one commit and merges the reviewed PR into that owner's fork main branch. Current work remains in the fmarslan forks; no YouthOpp upstream PR is requested.

## Propose a source

Include the publisher name, country, original URL, supported languages, opportunity types, recent-update evidence and proposed access method. Prefer original institutions and reliable catalogs. Check published access guidance and avoid authentication bypass, excessive requests or full-text republication without permission.

An adapter must retain source URLs and source identifiers, document its schedule, use bounded network requests, and produce the shared schema. Use fixed fixtures for tests. Do not infer missing deadlines, funding, eligibility or locations. A failed source must not silently delete its last successful records.

## Work with AI openly

AI assistance is welcome. Disclose the role of AI in a contribution and verify every generated claim, source and test result. Agent-authored issue bodies, comments, PR descriptions and commit messages begin with `Open AI agent:`; identify the agent role after that prefix where useful. Do not place secrets, private profiles or sensitive application information in prompts or Git history.

## Recognition

The website may generate contributor profiles from public GitHub history. Scores represent documented project activity, not talent, reliability, eligibility or employment prospects. The published scoring method must state which repositories, revisions and activity types were included and which automated activity was excluded. Report attribution errors through a task or PR; do not manipulate activity to raise a score.

## Before submitting

- Check original-source attribution, dates and factual claims.
- Test the affected behaviour and explain limitations honestly.
- Check keyboard access, mobile layout and meaningful link text when changing UI.
- Keep English project documentation clear; preserve source language metadata.
- Follow the [code of conduct](CODE_OF_CONDUCT.md).
