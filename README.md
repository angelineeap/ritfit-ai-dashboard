# RITFIT AI Dashboard

## ▶ Preview it (click this)

**https://htmlpreview.github.io/?https://github.com/angelineeap/ritfit-ai-dashboard/blob/main/ritfit-ai-dashboard.html**

Opens the rendered dashboard in any browser — desktop or phone, no GitHub account, no login.
Bookmark it. This is the link to share.

> This repo is **public** (since 2026-09-13) so that the preview link above works without a
> login. It describes the internal agent system, so treat additions with care — see
> "Before you add anything" below.

## Why the other GitHub link shows code instead of the dashboard

Clicking `ritfit-ai-dashboard.html` on GitHub shows **a wall of HTML source** — in the file
view *and* the blame view. GitHub never renders HTML; no setting changes that. Always use the
htmlpreview link above.

## Offline copy

The HTML is a single self-contained file — no server, no internet, no setup. Download it and
double-click to open it offline. This is the fallback for when you want it on a plane, or in a
room with no wifi. It renders identically to the web version.

## Six pages

| Tab | What it shows |
|---|---|
| **Overview** | What the system delivers, and the eight-stage pipeline end to end |
| **The Team** | Each agent's role and what it is accountable for |
| **Workflow** | Every skill, grouped by the business stage it serves |
| **Grand Design** | The planned architecture, and progress against it |
| **Reference** | Searchable skill cards, the who-has-what matrix, the chains |
| **Idea Bank** | Skills under consideration, rated on fit and on how proven they are |

`RITFIT-AI-Family-Tree-v5-ASCII.md` is the same system as plain text. That is the version to
paste into Feishu, a doc, or a slide.

## The HTML is generated — do not hand-edit it

Rebuilt from the live agent configuration, so it cannot drift out of date. **Edits to the HTML
are erased on the next build, by design.** Maintained by the `ritfit-ai-dashboard` skill.
`README.md` (this file) is *not* generated — edit it freely.

## Before you add anything to this repo

It is public, permanent, and indexed, and flipping it back to private does **not** reliably
un-index what crawlers already took. Before adding a file, check it for internal identifiers —
Feishu app IDs (`cli_…`), chat IDs (`oc_…` / `ou_…`), emails, and machine paths. The published
files today contain none of those; the only internal identifier is the Feishu base token for
the RITFIT KOL Workspace base, which is an identifier rather than a credential.

## Why this is a separate repo

Deliberately kept apart from `ritfit-skills`, which is what the marketing team clones. That repo
is private and skill-only; this one holds internal architecture and is public for the preview
link above.
