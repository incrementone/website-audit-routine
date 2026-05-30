# IncrementOne Website Audit Standards
*Version 1.0 — May 2026 | One-time setup document. Use as input for all monthly audits.*

---

## Scoring Rubric (applies across all three domains)

| Score | Label | Meaning |
|-------|-------|---------|
| 5 | Best-in-class | Fully implemented, no meaningful gaps vs. leading B2B consulting/training firms |
| 4 | Strong | Implemented with minor gaps; competitive but improvable |
| 3 | Functional | Present but incomplete; average for the category |
| 2 | Weak | Partially present or poorly executed; below-average |
| 1 | Missing | Not present or fundamentally broken |

**Benchmark audience:** B2B buyer in a Canadian SMB or mid-market enterprise evaluating an agile consulting or training firm. Buyer is typically a VP, Director, or senior delivery leader. They are research-led, trust-sensitive, and evaluating credibility before making contact.

---

## Domain 1: SEO (Search Engine Optimization)

Standards are derived from Google's documented ranking signals: Core Web Vitals, E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness), and technical hygiene criteria.

### 1.1 Title Tags & Meta Descriptions
- Each page has a unique, descriptive `<title>` tag (50–60 characters)
- Each page has a unique meta description (140–160 characters) written to drive click-through, not just describe
- Title tags lead with the primary keyword, not the brand name (exception: homepage)
- **Score 5:** Every audited page meets all three criteria with buyer-intent language
- **Score 3:** Present on most pages but generic, duplicated, or keyword-free
- **Score 1:** Missing, auto-generated, or identical across pages

### 1.2 Heading Hierarchy (H1–H3)
- One H1 per page, containing the primary keyword for that page
- H2s used to structure page sections logically, H3s for sub-points
- No skipped heading levels
- **Score 5:** Every audited page has a clean, keyword-grounded hierarchy
- **Score 3:** H1 present but not keyword-aligned; H2s inconsistent
- **Score 1:** H1 missing or multiple H1s present

### 1.3 E-E-A-T Signals (Experience, Expertise, Authoritativeness, Trustworthiness)
- Named authors with credentials on all blog/thought leadership content
- Author bios link to credentials (certifications, LinkedIn, track record)
- Testimonials include full name, title, and company
- Social proof: client logos, case studies, or measurable outcomes present
- **Score 5:** All signals present and substantiated; no anonymous content
- **Score 3:** Some signals present; testimonials lack specifics; author bios thin
- **Score 1:** No author attribution; no verifiable credentials on site

### 1.4 Keyword Targeting & Semantic Relevance
- Each service page targets a primary keyword and 2–3 semantic variants
- Keywords appear naturally in H1, first paragraph, and at least one H2
- Content addresses the buyer's problem, not just the firm's methodology
- **Score 5:** Each page has a clear primary keyword; buyer-problem framing throughout
- **Score 3:** Keywords present but inconsistent; content leans toward firm-centric language
- **Score 1:** No discernible keyword strategy; content is entirely methodology-led

### 1.5 Internal Linking Structure
- Key service pages are linked from multiple other pages (homepage, blog, about)
- Blog/Perspectives articles link back to relevant service pages
- No orphan pages (pages with zero inbound internal links)
- Navigation is consistent and crawlable
- **Score 5:** All service pages well-linked; blog posts connect to relevant services
- **Score 3:** Homepage links to services but blog/about do not; orphan pages likely
- **Score 1:** Navigation-only linking; no contextual internal links

---

## Domain 2: Web Standards & Technical Health

Standards derived from Google Search Central documentation, W3C specifications, and WCAG 2.1 AA accessibility guidelines.

### 2.1 HTTP Status Codes (4xx/5xx errors)
- All internal links resolve to 200 OK
- No broken links (404s) on any audited page
- Redirects (301/302) used appropriately where URLs have changed
- **Score 5:** Zero broken internal links across all audited pages
- **Score 3:** 1–3 broken links, non-critical pages
- **Score 1:** Multiple broken links on key pages (homepage, services, about)

### 2.2 Page Speed & Core Web Vitals
- Largest Contentful Paint (LCP): ≤ 2.5s (good) / 2.5–4s (needs improvement) / >4s (poor)
- Cumulative Layout Shift (CLS): ≤ 0.1 (good) / 0.1–0.25 (needs improvement) / >0.25 (poor)
- Interaction to Next Paint (INP): ≤ 200ms (good) / 200–500ms (needs improvement) / >500ms (poor)
- Images use modern formats (WebP/AVIF) and are appropriately sized
- **Score 5:** All three Core Web Vitals in "good" range on mobile and desktop
- **Score 3:** One or two vitals in "needs improvement"; desktop passes but mobile fails
- **Score 1:** One or more vitals in "poor" range

### 2.3 Mobile Responsiveness
- All pages render correctly on 375px–414px viewport widths
- No horizontal scrolling, text overflow, or tap target issues
- CTAs and forms function on mobile
- **Score 5:** Fully responsive across all tested viewports; no layout breaks
- **Score 3:** Generally responsive but with minor layout issues on mobile
- **Score 1:** Layout breaks, unreadable text, or non-functional forms on mobile

### 2.4 Structured Data (Schema Markup)
- Organization schema on homepage (name, URL, logo, contact, social profiles)
- LocalBusiness or ProfessionalService schema where appropriate
- Article/BlogPosting schema on Perspectives posts (with author, datePublished, dateModified)
- FAQ schema on pages with Q&A sections
- **Score 5:** All four schema types implemented and validated (no errors in Rich Results Test)
- **Score 3:** Organization schema present; blog and FAQ schema missing
- **Score 1:** No schema markup present

### 2.5 Crawlability & Indexability
- robots.txt present and not blocking key pages
- XML sitemap present, submitted to Google Search Console, and up to date
- Canonical tags correctly set on all pages (no self-referential duplicates or cross-page conflicts)
- No accidental noindex tags on public pages
- **Score 5:** All four elements present and correctly configured
- **Score 3:** robots.txt and sitemap present; canonicals inconsistent; no GSC submission confirmed
- **Score 1:** Sitemap missing or robots.txt blocking key pages

---

## Domain 3: GEO (Generative Engine Optimization / LLM Citation-Readiness)

**Framing note:** GEO standards are emerging and not yet governed by a canonical specification. The criteria below are derived from convergent research across multiple 2025–2026 studies and practitioner analyses (Princeton GEO study, Search Engine Land, Enrich Labs, Frase.io). They reflect what is demonstrably influencing citation rates in ChatGPT, Perplexity, Claude, and Google AI Overviews as of mid-2026.

**Core principle:** LLMs select and cite sources that are factual, directly answerable, structurally extractable, and authoritative. A site optimized for GEO reads like a trustworthy expert giving a direct answer — not like a brochure.

### 3.1 Direct-Answer Openings (TLDR-First Structure)
- Each key page answers its primary question in the first 40–60 words
- Service pages open with what the service does and who it is for — not with a hook or philosophy statement
- Blog posts front-load the conclusion or key finding, not the narrative build-up
- **Score 5:** All audited pages answer the primary query in the opening paragraph
- **Score 3:** Some pages open with direct answers; others lead with brand philosophy
- **Score 1:** All pages lead with narrative, philosophy, or positioning — no direct answers

### 3.2 Fact Density & Quantified Claims
- Content includes specific, verifiable facts, statistics, or named frameworks every 150–200 words
- Claims are attributed to named sources, research, or documented client outcomes
- Outcome-based testimonials include measurable results where possible
- **Score 5:** Regular fact/data cadence throughout key pages; attributed claims throughout
- **Score 3:** Some facts present; mostly qualitative; testimonials lack measurable outcomes
- **Score 1:** All qualitative; no data, no named frameworks, no attributed research

### 3.3 Entity Clarity (Who, What, Where)
- The site clearly and consistently names: the firm (IncrementOne), its founders/principals (Dave Sharrock), its proprietary frameworks (Product Office, PDI), its geography (Canada/Vancouver), and its ICP
- These entities appear in consistent form across all pages (no variation in naming)
- A dedicated About page establishes the principals with enough biographical depth to be cited
- **Score 5:** All key entities named consistently across all pages; About page is citation-ready
- **Score 3:** Firm name consistent; founder credentials thin on most pages; frameworks named but not explained
- **Score 1:** Founder not named on key pages; proprietary frameworks unnamed or inconsistently labeled

### 3.4 Extractable Structure (Q&A, Lists, Definitions)
- Key pages include at least one FAQ section, bulleted list, or numbered process — content that an LLM can extract as a discrete chunk
- Service pages include a "What changes when you get this right?" or similar outcomes section in extractable format
- Blog posts include section headers that function as standalone questions or claims
- **Score 5:** Most pages have at least one extractable structure element; FAQ schema applied
- **Score 3:** Some bullet lists present; no FAQ sections; section headers are labels not questions
- **Score 1:** Pure prose throughout; no extractable structure elements

### 3.5 Off-Site Authority & Citation Signals
- The firm or its principals are mentioned/cited on external sites (media, industry bodies, Scrum Alliance, podcast directories, LinkedIn)
- Wikipedia or Wikidata entity page exists for the firm or founder
- Backlink profile includes links from relevant industry domains (not just directories)
- **Score 5:** Multiple credible external citations; Scrum Alliance profile active; podcast indexed
- **Score 3:** Podcast indexed; Scrum Alliance present; no media or Wikipedia presence
- **Score 1:** Minimal external presence; backlinks limited to directories

---

## Monthly Audit Scope

**Pages to audit each month:**
1. Homepage (`/`)
2. Product Delivery / The Product Office (`/services/the-product-office`)
3. Facilitated Training / Corporate Training (`/services/corporate-training`)
4. Cyber-security (`/cyber-security`)
5. Learning Centre / Product Delivery Index (`/pdi`)
6. About Us (`/about-us`)
7. Approach (`/approach`)
8. B-Corp Business (`/b-corp-business`)
9. Perspectives / Blog (`/perspectives`)
10. One Perspectives article (rotate monthly)

**Tools to use (external, not included here):**
- Google Search Console: crawl errors, Core Web Vitals field data, index coverage
- Google Rich Results Test: schema validation
- Screaming Frog or Ahrefs: 4xx/5xx detection, internal link audit
- PageSpeed Insights: Core Web Vitals lab data
- Manual LLM test: query ChatGPT, Perplexity, and Google AI Overviews for "agile consulting Canada", "product delivery transformation", "Scrum training Vancouver" and note whether IncrementOne is cited

**Output format:** Use the Hit List table template (see companion document).

---

*Last updated: May 2026. Review and update GEO criteria quarterly — this domain is evolving rapidly.*
