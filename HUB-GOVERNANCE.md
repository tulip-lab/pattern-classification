# Shared Multi-Institution Hub Governance

## Public layers

This repository has two public layers:

1. **Common core** — institution-neutral modules, learning outcomes, activities,
   and public references.
2. **Offering layers** — institution-, unit-, and teaching-period-specific
   navigation and approved public assessment information.

The stable common-core entry points are `M01-Induction/` through `M11-Privacy/`.

The public Lab repository is the primary student-facing working site. It owns
the mutable practical chapters and notebooks, public assignment packages, issue
tracking, and pull-request workflow. This repository owns the stable common
core, module identities, learning outcomes, and public offering index.

## Common-core rules

Common-core content must use institution-neutral language, observable learning
outcomes, stable public dependencies, and accessible learning guidance. It must
not state current university dates, submission systems, policy wording, active
assessment instructions, or staff contact details.

## Offering rules

Use this path pattern:

```text
offerings/<institution>/<unit>/<offering>/
```

Each offering must state its status and common-core dependency. It may contain
public schedules, assessment briefs, dates, collaboration rules, submission
instructions, and links to current institutional policies. It must not contain
solutions, marking guides, hidden tests, student information, credentials,
private links, or restricted data.

Offering status is one of `planned`, `active`, `superseded`, or `archived`.
Archived material must carry a visible warning and must not be presented as
current instructions.

## Canonical-source rule

Every artefact has one editable canonical source. Public-native common-core
content is canonical here. Public-native practical content is canonical in the
Lab repository. Assessment and offering material promoted from the private
Instructor repository is a reviewed public snapshot and must retain its source
identity and release status.

Student and community improvements to practical material should be proposed as
pull requests in the Lab repository. Do not duplicate an editable Lab artefact
inside the common core or use a public pull request to submit assessed work.

## Release boundary

Before publishing or updating an offering, confirm the exact candidate,
classification, rights, privacy, accessibility, links, dates, policy sources,
and rollback path. Approval for one public repository does not authorise a
different destination.
