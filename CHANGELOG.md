# Changelog

All notable changes to this project are documented here.
This project follows [Semantic Versioning](https://semver.org/).

## [1.0.0] - 2026-06-23

First public release — the launcher plus four Brightspace (D2L) admin tools in one self-contained HTML file.

### Tools
- **Bulk Group Creator** — create groups with dynamic, per-group descriptions generated from an Excel sheet (member names, emails, roles).
- **Bulk Grades & Feedback Uploader** — upload grades and written feedback (including private instructor comments) from one spreadsheet.
- **Discussions Report & Export** — view every post across all forums and topics, with replies, attachment links, live name search, and Excel export.
- **Checklist Report & Export** — view whole-class checklist progress and export it.

### Highlights
- Single file — no build step, nothing else to upload.
- Works on any Brightspace instance; course context comes from the `{OrgUnitId}` / `{OrgUnitName}` replace strings.
- Built on the Brightspace Valence API using the user's existing session; auto-detects the instance's latest API versions.
- One launcher; each tool runs isolated so they never conflict.
- Themeable via a single `SUITE_CONFIG` block (brand colour, logo, title, attribution).

### Install
Paste the contents of `AdminAcceleratorSuite.html` into a Brightspace Content page (source view) or a Custom Widget, then save. See the README for full steps.

[1.0.0]: https://github.com/John-Morrissey-UL/admin-accelerator-suite/releases/tag/v1.0.0
