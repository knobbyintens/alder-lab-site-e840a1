# Alder Ridge Lab - Website

Source repository for the public website of the Alder Ridge Lab.

Every publication of the lab has one Markdown page under `publications/`.
Pages use YAML front matter with the following keys:

```yaml
title: "..."
authors: "..."
venue: "..."
year: 2026
code_url: ""
type: "conference"
```

`venue` records the current publication status (a venue name, or
`Under review` / `Preprint` while a decision is pending). `code_url` stays
empty until the project's software release is publicly available.

Release notes for the lab's software projects live under `software/`
(one folder per project, each with a README describing its release status).
