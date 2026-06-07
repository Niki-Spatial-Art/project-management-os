# Repositories

## Owned

| Name | URL | Type | Status | Why It Matters |
|---|---|---|---|---|
| project-management-os | https://github.com/Niki-Spatial-Art/project-management-os | core | active | Main repository for project workflows, templates, and review loops. |
| codex-workbench-hub | https://github.com/Niki-Spatial-Art/codex-workbench-hub | hub | active | Private hub for cross-repo navigation, automation indexes, and shared operating context. |
| investment-research-lab | https://github.com/Niki-Spatial-Art/investment-research-lab | adjacent | active | Category repository for investment research workflows, tools, and references. |
| content-production-lab | https://github.com/Niki-Spatial-Art/content-production-lab | adjacent | active | Category repository for writing, publishing, layout, and distribution systems. |
| knowledge-system-lab | https://github.com/Niki-Spatial-Art/knowledge-system-lab | adjacent | active | Category repository for knowledge capture, retrieval, note structures, and publishing patterns. |
| personal-growth-lab | https://github.com/Niki-Spatial-Art/personal-growth-lab | adjacent | active | Category repository for privacy-safe personal growth systems and framework-based habit references. |

## External References

| Name | URL | Type | Status | Why Track It |
|---|---|---|---|---|
| GitHub Projects Docs | https://docs.github.com/en/issues/planning-and-tracking-with-projects | official-docs | active | Canonical reference for GitHub-native planning, roadmaps, and project automation. |
| OpenProject | https://github.com/opf/openproject | project-suite | active | Mature open-source project management suite worth mining for structure and workflow ideas. |
| Taiga Docker | https://github.com/taigaio/taiga-docker | project-suite | active | Self-hostable agile PM reference with backlog, sprint, and integration patterns distinct from OpenProject and Plane. |
| Atlassian Team Playbook | https://www.atlassian.com/team-playbook | playbook | active | Useful source for reusable meeting, goal-setting, and retrospective operating patterns. |
| MADR | https://github.com/adr/madr | adr-template | active | Well-adopted ADR template for consistent decision records. |
| Google Cloud ADR Guidance | https://cloud.google.com/architecture/architecture-decision-records | official-docs | active | Practical official guidance for writing high-signal architecture decision records. |
| GitHub Mermaid Diagram Docs | https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams | official-docs | active | Useful for keeping roadmaps, process maps, and ADR diagrams directly in Markdown without extra tooling. |

## Fork Candidates

| Name | URL | Decision | Notes |
|---|---|---|---|
| Plane | https://github.com/makeplane/plane | review | Full-featured open-source project management product worth studying for issue, project, and wiki integration patterns. |
| backlog.md | https://github.com/MrLesk/backlog.md | watch | Git-native task management approach that could inspire a lighter CLI-centric workflow. |
| Kanboard | https://github.com/kanboard/kanboard | watch | Lightweight Kanban baseline worth comparing against heavier suites when a simpler self-hosted board is enough. |

## Cross-Repo Refresh Queue

Reviewed on 2026-06-07. These candidates are suitable for the public category repositories and the private hub when those repositories are writable from the automation workspace.

### Investment Research

| Name | URL | Type | Why It Matters |
|---|---|---|---|
| OpenBB Python Extensions Docs | https://docs.openbb.co/odp/python/extensions | official-docs | Adds provider and extension architecture context around the existing OpenBB repository entry. |
| Microsoft Qlib | https://github.com/microsoft/qlib | platform | Mature quantitative research framework for data pipelines, experiment tracking, and AI-assisted modeling. |
| SEC EDGAR API Documentation | https://www.sec.gov/edgar/sec-api-documentation | official-docs | Canonical public-filings source for reproducible US fundamental research workflows. |
| sec-edgar-downloader | https://github.com/jadchaar/sec-edgar-downloader | library | Practical Python wrapper for downloading SEC filings into local research pipelines. |
| ArcticDB | https://github.com/man-group/arcticdb | data-infrastructure | Versioned DataFrame store for reproducible market datasets, point-in-time snapshots, and larger research caches. |
| ArcticDB Docs | https://docs.arcticdb.io/ | official-docs | Useful for evaluating local-first LMDB setups versus S3-backed research storage without adding much infrastructure. |
| PyPortfolioOpt | https://github.com/PyPortfolio/PyPortfolioOpt | portfolio-optimization | Practical portfolio-construction toolkit for efficient frontier, Black-Litterman, and constraint-aware allocation experiments. |

### Content Production

| Name | URL | Type | Why It Matters |
|---|---|---|---|
| Quarto CLI | https://github.com/quarto-dev/quarto-cli | publishing | Reproducible publishing stack for reports, articles, sites, and slides from Markdown or notebooks. |
| Quarto Publishing Docs | https://quarto.org/docs/publishing/ | official-docs | Useful for CI-friendly publishing flows across GitHub Pages and other targets. |
| Marp CLI | https://github.com/marp-team/marp-cli | slides | Lightweight Markdown-to-slides workflow for repeatable deck generation. |
| Eleventy | https://github.com/11ty/eleventy | static-site | Strong option for content libraries, archives, and editorial microsites without a heavy framework. |
| Typst | https://github.com/typst/typst | typesetting | Modern programmable typesetting engine for polished report-style outputs. |
| Material for MkDocs | https://github.com/squidfunk/mkdocs-material | docs-publishing | High-signal choice for searchable documentation hubs, playbooks, and knowledge-heavy publishing without a heavy app stack. |
| Material for MkDocs Docs | https://squidfunk.github.io/mkdocs-material/ | official-docs | Useful for navigation, search, and content-architecture patterns when building long-lived documentation sites. |
| Pandoc | https://github.com/jgm/pandoc | document-conversion | Strong interoperability layer when the workflow needs to move cleanly across Markdown, DOCX, PDF, EPUB, and slides. |

### Knowledge Systems

| Name | URL | Type | Why It Matters |
|---|---|---|---|
| Memos | https://github.com/usememos/memos | local-first | Good reference for quick capture, backlinks, and self-hosted note workflows. |
| AppFlowy | https://github.com/AppFlowy-IO/AppFlowy | workspace | Open-source workspace stack with a strong local-first and knowledge-organization angle. |
| SilverBullet | https://github.com/silverbulletmd/silverbullet | local-first | Markdown-native PKM with scripting and wiki patterns worth studying. |
| SilverBullet Manual | https://silverbullet.md/Manual | official-docs | Explains the product model, sync assumptions, and scripting primitives. |
| Joplin | https://github.com/laurent22/joplin | note-system | Mature open-source note system with sync, publishing, and plugin patterns worth comparing against graph-first tools. |
| Joplin Sync Spec | https://joplinapp.org/help/dev/spec/sync/ | official-docs | Helpful for understanding conflict handling, sync targets, and offline-first design tradeoffs in a knowledge stack. |

### Personal Growth

Framework-only and privacy-safe. Keep any downstream notes suitable for a lightweight 173 cm / 55 kg reference range, and avoid medical claims or sensitive personal data.

| Name | URL | Type | Why It Matters |
|---|---|---|---|
| Loop Habit Tracker | https://github.com/iSoron/uhabits | habits | Strong offline-first habit system with durable scoring ideas and export patterns. |
| wger | https://github.com/wger-project/wger | fitness-workflow | Privacy-friendly training and nutrition workflow reference for system design, not personal logging. |
| WHO Physical Activity Guidelines | https://www.who.int/publications/i/item/9789240015128 | official-guidance | Credible non-medical baseline for activity-planning language and safety framing. |
| Open Food Facts | https://world.openfoodfacts.org/ | food-data | Open public food database useful for nutrition-reference workflows without sensitive personal data. |
| Habitica | https://github.com/HabitRPG/habitica | habits | Gamified recurring-task and streak ideas worth studying for motivation loops without storing sensitive personal data here. |
| CDC Adult Activity Overview | https://www.cdc.gov/physical-activity-basics/guidelines/adults.html | official-guidance | Clear public baseline for weekly movement and strength planning language without drifting into medical claims. |

### Hub Propagation

| Target | Notes |
|---|---|
| codex-workbench-hub `repo-map/repositories.md` | Mirror the category-specific additions above so the private hub stays aligned with the public category indexes. |

## Run Constraints

| Area | Constraint |
|---|---|
| Sibling category repositories | Readable from this workspace, but not writable under the current sandbox policy. |
| Private hub repository | Readable from this workspace, but not writable under the current sandbox policy. |
| Push operations | Not attempted yet in this run; local branch is already ahead of origin from the previous automation commit. |
