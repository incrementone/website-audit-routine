# IncrementOne Website Audit — June 2026
*Audit date: 2026-06-01 | Standards version: 1.0*
*Rotating article audited: "Your Impact In 2025" — https://www.incrementone.com/perspectives/your-impact-in-2025*

*No prior report found — trend column omitted this run. Template file `incrementone-audit-YYYY-MM.md` detected in `reports/` but treated as placeholder, not a dated prior report.*

---

## Fetch Log

| Page | Status | Notes |
|------|--------|-------|
| Homepage | ✓ Fetched | — |
| The Product Office | ✓ Fetched | — |
| Facilitated Training | ✓ Fetched | — |
| Cyber Security | ✓ Fetched | — |
| Product Delivery Index | ✓ Fetched | — |
| About Us | ✓ Fetched | — |
| Approach | ✓ Fetched | — |
| B Corp Business | ✓ Fetched | — |
| Perspectives (blog listing) | ✓ Fetched | — |
| Rotating article: "Your Impact In 2025" | ✓ Fetched | Published May 26, 2026; most recent article with no prior audit history |

**Fetch failures:** None. All 10 pages returned content successfully.

**Rotating article selection:** No prior reports exist, so the most recently published article was selected: "Your Impact In 2025" (May 26, 2026).

---

## Score Summary

| # | Criterion | Current Score | Prior Score | Change | Finding |
|---|-----------|--------------|-------------|--------|---------|
| 1.1 | Title Tags & Meta Descriptions | 2/5 | — | — | Service page titles lead with section labels ("Our Services -") rather than primary keywords; no meta descriptions recoverable from any audited page. |
| 1.2 | Heading Hierarchy | 2/5 | — | — | Homepage renders two H1-level headings ("People Powered Change" and "Understand Your Organizational DNA"); H1s on Approach, About Us, and Cyber Security are not keyword-aligned. |
| 1.3 | E-E-A-T Signals | 3/5 | — | — | All testimonials include full name, title, and company; Cyber Security page names four practitioners with years of experience; blog author bios lack inline credentials and About Us team profiles are thin. |
| 1.4 | Keyword Targeting | 2/5 | — | — | All service pages frame content around IncrementOne's methodology and branded frameworks rather than buyer-searched problem language such as "agile consulting Canada" or "Scrum training Vancouver." |
| 1.5 | Internal Linking | 3/5 | — | — | Primary navigation consistently links to all service pages from every audited page, but the audited Perspectives article contains no contextual links back to any service page. |
| 2.1 | HTTP Status Codes | 3/5 | — | — | All 10 audited URLs returned accessible content with no failures; no broken internal links detected within audit scope, but full verification requires Screaming Frog. |
| 2.2 | Core Web Vitals | Requires external tool | — | — | Run PageSpeed Insights on all key pages; cannot be assessed from HTML content alone. |
| 2.3 | Mobile Responsiveness | 3/5 | — | — | Viewport meta tag confirmed present across all 10 audited pages indicating responsive design configuration; actual rendering on 375–414px viewports cannot be verified from content alone. |
| 2.4 | Structured Data | 1/5 | — | — | No JSON-LD, schema.org markup, or any other structured data surfaced on any audited page, including the homepage, service pages, or the Perspectives article. |
| 2.5 | Crawlability & Indexability | 3/5 | — | — | Canonical tag confirmed present on the Product Office page; no noindex signals detected on any audited page; robots.txt and XML sitemap status require manual verification. |
| 3.1 | Direct-Answer Openings | 2/5 | — | — | Eight of ten audited pages open with brand philosophy statements, positioning hooks, or section labels rather than a direct answer to the buyer's primary query for that page. |
| 3.2 | Fact Density & Quantified Claims | 2/5 | — | — | Service pages are predominantly qualitative; only the Cyber Security page offers quantified credentials (17 and 30+ years experience) and the B Corp page includes specific charity percentages; no attributed research or measurable client outcomes appear on any service page. |
| 3.3 | Entity Clarity | 3/5 | — | — | "IncrementOne" appears consistently across all pages and Dave Sharrock is identified on About Us and article bylines, but geographic identity (Vancouver/Canada) and ICP description are not consistently stated across service pages. |
| 3.4 | Extractable Structure | 3/5 | — | — | Most service pages include numbered frameworks and process steps (Facilitated Training's 4-step framework, Cyber Security's 4-stage journey, PDI's 5 dimensions); no FAQ sections detected on any audited page. |
| 3.5 | Off-Site Authority | Requires external tool | — | — | Run Ahrefs or similar; podcast "Definitely, Maybe Agile" is referenced on the Perspectives page indicating some off-site presence, but backlink profile and external citation count cannot be assessed from page content. |

**Domain averages:**
- SEO: 2.4 / 5 (prior: —)
- Web Standards: 2.5 / 5 (prior: —) *(average of scoreable criteria 2.1, 2.3, 2.4, 2.5 only; 2.2 excluded)*
- GEO: 2.5 / 5 (prior: —) *(average of scoreable criteria 3.1, 3.2, 3.3, 3.4 only; 3.5 excluded)*

---

## Hit List — SEO (Top 5)

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | Title tags not keyword-led; meta descriptions absent | All 10 | 2/5 | 5/5 | Rewrite all service page titles to lead with the primary buyer keyword (e.g., "Agile Product Delivery Consulting \| IncrementOne"); write unique 140–160-character meta descriptions for every audited page using buyer-intent language and a CTA hook | High — directly affects whether buyers searching "agile consulting Canada" or "Scrum training Vancouver" find these pages |
| 2 | Keyword targeting is firm-centric throughout | 8/10 (all service + approach pages) | 2/5 | 5/5 | Audit each service page for a primary keyword and 2–3 semantic variants; rewrite H1, first paragraph, and at least one H2 per page to frame the buyer's problem before introducing IncrementOne's solution | High — search engines rank pages on query relevance; methodology-first language is invisible to buyers who don't know the firm |
| 3 | Multiple H1s on homepage; H1s on 3 pages lack keyword alignment | 4/10 | 2/5 | 5/5 | Consolidate the homepage to a single keyword-aligned H1; update Approach, About Us, and Cyber Security H1s to include a primary keyword (e.g., "Cybersecurity Integration for Agile Teams") | Medium — heading structure is a ranking signal and affects LLM parsing; multiple H1s signal poor semantic structure |
| 4 | E-E-A-T signals incomplete: thin author bios, no credentialled testimonials | 6/10 (blog + service pages) | 3/5 | 5/5 | Add credential bylines to all blog post authors (Scrum Alliance certifications, LinkedIn URL); expand About Us bios with measurable career outcomes; add at least one testimonial per service page that names a specific measurable result | High — trust signals are a primary factor for a B2B buyer evaluating a consulting firm before making contact |
| 5 | Blog articles lack contextual links to service pages | 2–3/10 (blog/perspectives pages) | 3/5 | 5/5 | Add one contextual internal link from each Perspectives article to the most relevant service page; add at least two contextual service links to the About Us and Approach pages | Medium — contextual linking distributes authority to service pages and guides buyers deeper into the funnel |

*Priority weights: 1.1 = 9, 1.4 = 9 (fewer pages breaks tie), 1.2 = 6 (more pages than 1.3), 1.3 = 6, 1.5 = 4*

---

## Hit List — Web Standards (Top 5)

*Only 4 genuine scoreable issues identified; not padded to 5.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | No structured data markup detected on any page | All 10 | 1/5 | 5/5 | Implement Organization schema (name, URL, logo, social profiles) on the homepage; add Article/BlogPosting schema (author, datePublished, dateModified) to all Perspectives posts; implement FAQ schema on any page with a Q&A section; validate with Google Rich Results Test | Medium — zero schema means no rich snippets in SERPs, no entity recognition by search engines, and missed LLM training signals |
| 2 | Crawlability unverified: canonical consistency and sitemap status unknown | All 10 | 3/5 | 5/5 | Confirm canonical tags are set correctly on all 10 pages (not just the Product Office page); verify robots.txt is not blocking any service pages; submit and verify XML sitemap in Google Search Console | High — if any page is misconfigured as noindex or blocked by robots.txt, it disappears from search entirely |
| 3 | Mobile rendering unverified beyond viewport meta tag | All 10 | 3/5 | 5/5 | Run all 10 audited pages through Google Mobile-Friendly Test; check for horizontal scroll, text overflow, and tap-target failures at 375px and 414px viewports; fix any issues found | High — B2B buyers increasingly research on mobile; any layout break increases bounce rate and reduces trust |
| 4 | HTTP status code coverage limited to audit scope | All 10 (audit scope only) | 3/5 | 5/5 | Run a full crawl with Screaming Frog to surface any 4xx or 5xx responses across all internal links; fix or redirect any broken URLs found | Medium — broken internal links harm crawl budget and user experience; current audit found no breaks but full coverage was not possible |

*Priority weights: 2.4 = 8, 2.5 = 6 (foundational), 2.3 = 6 (direct buyer impact), 2.1 = 6 (no current evidence of issues)*

---

## Hit List — GEO (Top 5)

*Only 4 genuine scoreable issues identified; not padded to 5.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | Pages open with brand philosophy, not direct answers | 8/10 | 2/5 | 5/5 | Rewrite the first 40–60 words of each service page to answer the buyer's primary query directly (e.g., "The Product Office is IncrementOne's embedded delivery system for mid-market organizations that need..."); move philosophical positioning to a secondary section | High — LLMs select and cite content that answers the query in the opening; philosophy-first pages are systematically skipped |
| 2 | Service pages lack quantified claims and attributed research | 8/10 | 2/5 | 5/5 | Add at least 3 quantified client outcome statements per service page (cycle time, delivery velocity, team satisfaction scores); attribute all factual claims to named clients or published frameworks; include at least one specific number per H2 section | High — fact density is the strongest predictor of LLM citation; qualitative-only content is consistently passed over in favour of pages with numbers |
| 3 | No FAQ sections on any audited page | All 10 | 3/5 | 5/5 | Add a 3–5 question FAQ section to each of the three main service pages (Product Office, Facilitated Training, Cyber Security); frame questions as buyer objections or search queries (e.g., "What is the difference between a project office and a Product Office?"); apply FAQ schema | Medium — FAQ sections create extractable, discrete chunks that LLMs can quote verbatim; they also address buyer objections at the point of consideration |
| 4 | Founder name and geography absent from service pages | 6/10 | 3/5 | 5/5 | Add "Dave Sharrock, Founder" attribution or mention to the homepage and each service page intro; include "Vancouver, Canada" as a consistent geographic identifier on About Us, homepage, and at least two service pages | Medium — entity consistency (who, what, where) is a prerequisite for LLM citation; without it, the firm cannot be reliably identified and cited across queries |

*Priority weights: 3.1 = 9, 3.2 = 9 (fewer pages breaks tie), 3.4 = 4 (more pages breaks tie with 3.3), 3.3 = 4*

---

## Requires Manual Verification

The following criteria could not be scored from page content alone. These should be checked manually using the indicated tool before the next audit cycle:

| Criterion | Tool needed | Last manually checked |
|-----------|-------------|----------------------|
| 2.2 Core Web Vitals (LCP, CLS, INP) | PageSpeed Insights — run on mobile and desktop for Homepage, Product Office, Facilitated Training, and PDI pages at minimum | Never |
| 3.5 Off-Site Authority | Ahrefs or similar — check backlink profile for industry-domain links; check Scrum Alliance for Dave Sharrock profile; search ChatGPT, Perplexity, and Google AI Overviews for "agile consulting Canada" and "Scrum training Vancouver" | Never |

---

## Cross-Domain Priority Sequence

If bandwidth is limited this month, action in this order:

1. **Rewrite service page title tags to lead with buyer keywords and add meta descriptions to all 10 pages** — foundational for search discovery; currently all service pages lead with "Our Services -" or generic section labels
2. **Rewrite first 40–60 words of each service page to open with a direct answer** — highest combined SEO + GEO return; this single change improves keyword relevance, LLM citation rate, and bounce rate
3. **Add quantified client outcome statements to all three main service pages** — the absence of facts is the primary reason this site would be passed over by an LLM aggregating consulting recommendations
4. **Implement Organization schema on the homepage and Article schema on Perspectives posts** — zero structured data is the largest technical gap; schema is required for rich snippets and entity recognition
5. **Verify and complete canonical tag coverage across all pages, and confirm sitemap is in Google Search Console** — crawlability is a prerequisite for every other SEO improvement to take effect

*Sequence based on: score gap × buyer-journey impact, across all three domains.*

---

*Next audit: July 2026 | Report generated by website-audit-routine v1.0*
