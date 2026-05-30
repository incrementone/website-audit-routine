# IncrementOne Website Audit Routine

A Claude Code routine that runs a structured monthly audit of `www.incrementone.com` against three standard domains — SEO, Web Standards, and GEO — and produces a scored, prioritised hit list as a dated Markdown report.

---

## What it does

Each run:
1. Fetches the 10 pages in the audit scope
2. Scores each page against the 15 criteria in the standards document (5 per domain)
3. Selects the top 5 highest-impact issues per domain
4. Writes a new dated report to `reports/`

It runs autonomously start to finish. No mid-run prompts.

---

## Directory structure

```
website-audit-routine/
├── CLAUDE.md                          # Agent charter (behaviour rules)
├── README.md                          # This file
├── routines/
│   └── website-audit.md               # Step-by-step execution instructions
├── standards/
│   └── incrementone-website-standards.md   # Scoring rubric and criteria (read-only)
└── reports/
    └── incrementone-audit-YYYY-MM.md  # Generated — one file per monthly run
```

---

## Setup

### First run

1. Clone or copy this folder to your Claude Code workspace root
2. Confirm `standards/incrementone-website-standards.md` is present — the routine will halt without it
3. Run the routine (see below)

### Updating the standards document

The standards document is versioned. When you update it:
- Increment the version number in the document header
- Update the paired version reference in `CLAUDE.md` (`Standards document version this charter is paired with`)
- Old reports are not retroactively rescored — they reflect the standards version current at time of run

---

## Running the routine

From your Claude Code workspace root:

```
run website-audit-routine
```

Or trigger it by telling Claude Code:

> "Run the website audit routine for IncrementOne"

The routine will fetch pages, score them, and write the report to `reports/` with no further input needed.

---

## Output

Each run produces one file:

```
reports/incrementone-audit-2026-06.md
```

The report contains:
- **Score summary table** — current score per criterion, vs. previous month (if a prior report exists)
- **Fetch failures log** — any pages that could not be loaded, with reason
- **Hit list** — top 5 issues per domain, with current score, target score, fix description, and estimated impact
- **Priority sequence** — cross-domain ranked shortlist for when bandwidth is limited

Reports accumulate over time. Nothing is overwritten.

---

## Audit scope (pages)

The routine audits these 10 pages each month:

| # | Page | URL |
|---|------|-----|
| 1 | Homepage | `https://www.incrementone.com/` |
| 2 | The Product Office | `https://www.incrementone.com/services/the-product-office` |
| 3 | Facilitated Training | `https://www.incrementone.com/services/corporate-training` |
| 4 | Cyber Security | `https://www.incrementone.com/cyber-security` |
| 5 | Product Delivery Index | `https://www.incrementone.com/pdi` |
| 6 | About Us | `https://www.incrementone.com/about-us` |
| 7 | Approach | `https://www.incrementone.com/approach` |
| 8 | B Corp Business | `https://www.incrementone.com/b-corp-business` |
| 9 | Perspectives (blog listing) | `https://www.incrementone.com/perspectives` |
| 10 | One rotating Perspectives article | Rotate each month — see routine instructions |

---

## Scoring rubric

| Score | Label | Meaning |
|-------|-------|---------|
| 5 | Best-in-class | No meaningful gaps vs. leading B2B consulting/training firms |
| 4 | Strong | Implemented with minor gaps |
| 3 | Functional | Present but incomplete; average for the category |
| 2 | Weak | Partially present or poorly executed |
| 1 | Missing | Not present or fundamentally broken |
| N/V | Not Verified | Page could not be fetched; criterion unscored |

Full rubric and all 15 criteria are in `standards/incrementone-website-standards.md`.

---

## Limitations

- **JavaScript-rendered content:** The routine uses `web_fetch`, which retrieves server-rendered HTML. Webflow pages that depend heavily on client-side JS rendering may return incomplete content. Affected pages are logged and scored on what is visible; criteria requiring JS-rendered content are marked `N/V`.
- **Core Web Vitals:** LCP, CLS, and INP require PageSpeed Insights or Google Search Console field data — they cannot be measured via `web_fetch`. The routine flags these as `Requires external tool` and omits them from automated scoring. Run PageSpeed Insights manually once per month and add scores to the report.
- **External authority signals (GEO 3.5):** Backlink profile and off-site citations cannot be assessed without Ahrefs or similar. Flag as `Requires external tool`.
- **GEO standards:** The GEO domain criteria are derived from 2025–2026 practitioner research, not a canonical specification. Review and update `standards/incrementone-website-standards.md` quarterly.

---

## Maintenance schedule

| Task | Frequency | Owner |
|------|-----------|-------|
| Run the routine | Monthly | Dave / ops |
| Review and action the hit list | Monthly | Dave |
| Update GEO criteria in standards doc | Quarterly | Dave |
| Update audit scope if site structure changes | As needed | Dave |
| Update charter (`CLAUDE.md`) if agent behaviour needs to change | As needed | Dave |

---

*Routine version: 1.0 — May 2026*
