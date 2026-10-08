# SEU-PR2026 — Pattern Classification

> **Active offering:** this page is the authoritative public offering record for the 2026 Southeast University cohort. Operational updates that do not change the published task requirements will be announced by the teaching assistant in the course QQ group.

## Offering summary

| Item | Detail |
| --- | --- |
| Institution | Southeast University (SEU), 东南大学 |
| Course code | `SEU-PR2026` |
| Course name | Pattern Classification |
| Contact hours | 40 hours across four weeks |
| Group size | Normally three students; maximum four |
| Teaching assistant | 王扬翰; QQ `1694140651` |
| Course communication | QQ group `SEU-PR2026`; group number `1126406077` |

## Lecture handouts

Course handouts are password-protected. Download the required file from the course module page, then open it with the password supplied during class. Passwords are provided progressively as the relevant material is taught and are not published in the public repositories.

## Primary student site

Use the [Pattern Classification public portal](https://github.com/tulip-lab/pattern-classification) as the primary student site for course modules, handouts, the current offering, and authoritative course links. The [Pattern Classification Lab](https://github.com/tulip-lab/pattern-classification-lab/tree/develop) is the companion repository for runnable notebooks, practical sessions, and reusable assignment resources.

## Schedule

| Event | Date and time |
| --- | --- |
| Assignment 1 presentation session 1 | Friday, 30 October 2026; afternoon, China Standard Time |
| Assignment 1 presentation session 2 | Saturday, 31 October 2026; afternoon, China Standard Time |
| Final combined A1/A2 handoff | Package naming is fixed below; exact date, time, delivery route, and receipt process are announced by the teaching assistant in the course QQ group |

## Assessments

| Assignment | Weight | Student materials |
| --- | ---: | --- |
| A1 — Frontier AI through Pattern Classification | 25% | [Specification and topic catalogue](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/Assignments/frontier-ai-presentation) |
| A2 — Tourism demand forecasting | 75% | [Specification, starter notebook, CSV templates, and validator](https://github.com/tulip-lab/pattern-classification-lab/tree/develop/Assignments/tourism-demand-forecasting) |

### Assignment 1

Each group selects one of ten candidate topics organised under five themes:

1. Quantum Machine Learning;
2. privacy in quantum, LLM, and agentic AI;
3. counterfactual reasoning;
4. stochastic time-series and interval forecasting; and
5. Learngene for efficient knowledge transfer.

Each group receives 20 minutes for its presentation plus 5 minutes for questions. At least 5 presentation minutes must be an inspectable code or algorithm demonstration. Topics are not reserved, and multiple groups may independently select the same candidate.

### Assignment 2

Groups produce reproducible point and interval forecasts for monthly Chinese outbound tourism demand. The problem, data, temporal protocol, output schemas, and evaluation measures are fixed; the forecasting algorithm is open. Forecasting performance is the primary objective. Frontier methods are welcome, but novelty does not earn a separate bonus. The formal marking guide will be supplied through this offering when approved.

## Final handoff

A1 and A2 are not handed in separately. At the end of the course, one group representative submits one ZIP archive to teaching assistant 王扬翰, who collects and forwards the group packages to the lead instructor.

Choose a short group name containing 1–8 English letters or digits, with no spaces or punctuation. The Group ID is `Group-NAME`, for example `Group-Orion`. Confirm that the name is unique with the teaching assistant and use the same capitalisation everywhere. Do not add student names or student numbers to filenames.

Create this directory structure:

```text
Group-NAME-A1-A2/
├── A1/
│   ├── A1-Group-NAME-Slides.pdf
│   ├── A1-Group-NAME-Demo/
│   │   ├── README.md
│   │   └── <notebook, code, and required public data or retrieval instructions>
│   ├── A1-Group-NAME-References.pdf
│   └── A1-Group-NAME-Contributions.md
└── A2/
    ├── A2-Group-NAME-Notebook.ipynb
    ├── A2-Group-NAME-Report.pdf
    ├── A2-Group-NAME-Forecast.csv
    ├── A2-Group-NAME-Intervals.csv
    ├── A2-Group-NAME-Protocol.md
    ├── A2-Group-NAME-Model-Card.md
    └── A2-Group-NAME-Contributions.md
```

The A1 reproducibility record belongs inside `A1-Group-NAME-Demo/README.md`; no additional A1 metadata file is required. For A2, the Protocol records the rules fixed before the locked audit, the Report presents the comparative evidence and recommendation, and the Model Card gives a concise factual record of the frozen final system, its reproduction requirements, intended use, and limitations.

Compress the single parent directory as:

```text
Group-NAME-A1-A2.zip
```

Submit only this ZIP; do not submit separate A1 and A2 archives. Before submission, extract the ZIP into a new location, verify the directory and filenames, open both PDFs, run the A2 notebook from top to bottom, and validate the two CSV files. The teaching assistant announces the exact deadline, delivery route, receipt process, and any approved alternative in the course QQ group. If a cloud-sharing link is required, use OneDrive only and confirm that the link opens without a further access request. If email is requested, use the subject `[A1+A2] - Group-NAME`.

## Communication and privacy

Join QQ group **SEU-PR2026** using group number **1126406077**. The group carries schedule updates, Group ID notices, presentation order, clarifications, and final handoff instructions. The teaching assistant is **王扬翰**, QQ **1694140651**. Do not post student IDs, submissions, private form responses, personal evidence, or handout passwords in public channels.

For reusable theory, begin at the [Pattern Classification common core](../../../../README.md). For practical work and assignment files, use the [Pattern Classification Lab](https://github.com/tulip-lab/pattern-classification-lab).
