# Pattern Classification Open Repository Guidance

## Scope

This public repository contains the institution-neutral Pattern Classification
common core and approved public offering snapshots. Public common-core narrative
is canonical here; notebooks, code, data, and practical navigation are canonical
in `pattern-classification-lab`.

## Stable structure

Preserve the `M01`–`M11` module identities. Institution-specific dates,
submission channels, collaboration rules, policy text, and public assessment
briefs belong under `offerings/<institution>/<unit>/<offering>/`, never in the
common core.

## Public safety

Do not commit solutions, answer keys, marking guides, moderation, hidden tests,
student information, grades, identifiable feedback, credentials, private URLs,
restricted data, or private teaching notes. Keep material with unclear rights
out of the repository pending review.

## Content design

Use observable learning outcomes and align learning activities with the course
outcomes in `COMMON-CORE.md`. Keep practical details in the Lab repository and
link to its stable module page. Archived offerings must remain visibly archived.

## Validation

Inspect status before editing. For bounded content changes, check affected
links and structured files plus `git diff --check`. Treat offering publication,
licensing, privacy, assessment, path migration, and formal release claims as
governed work. Do not merge, push, tag, publish, or change repository visibility
without explicit authorization.
