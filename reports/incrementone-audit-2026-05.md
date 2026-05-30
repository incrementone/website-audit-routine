# IncrementOne Website Audit — May 2026
*Audit date: 2026-05-30 | Standards version: 1.0*
*Rotating article audited: Your Impact In 2025 — https://www.incrementone.com/perspectives/your-impact-in-2025*
*No prior report found — Prior Score and Change columns omitted.*

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
| Perspectives (blog listing) | ✓ Fetched | Most recent unaudited article identified: "Your Impact In 2025" (May 26, 2026) |
| Your Impact In 2025 (rotating article) | ✓ Fetched | https://www.incrementone.com/perspectives/your-impact-in-2025 |

No fetch failures on this run.

---

## Score Summary

*No prior report exists. Prior Score and Change columns are omitted for this run.*

| # | Criterion | Current Score | Finding |
|---|-----------|--------------|---------|
| 1.1 | Title Tags & Meta Descriptions | 2/5 | No meta descriptions detected on any of the 10 audited pages; six title tags fall below 30 characters (Cyber Security: "Cyber Security"; B Corp: "B Corp Business"; About: "About Us \| IncrementOne"; PDI: "PDI (Product Delivery Index)"; Approach: "Our Approach \| IncrementOne"; Article: "Your Impact In 2025 \| IncrementOne"), and two service page titles lead with the generic prefix "Our Services -" rather than the primary keyword. |
| 1.2 | Heading Hierarchy (H1–H3) | 2/5 | Homepage carries two H1s ("People Powered Change" and "Understand Your Organizational DNA"), which is a direct technical violation; across all remaining pages H1s are brand philosophy statements or generic labels ("Our Approach", "About Us", "Perspectives") rather than keyword-grounded headings. |
| 1.3 | E-E-A-T Signals | 3/5 | Testimonials on Homepage, Corporate Training, and Approach include full name, title, and company — a solid foundation; however, the Perspectives listing shows several articles attributed to "IncrementOne" rather than a named individual, and author bios linking to external credentials (Scrum Alliance, LinkedIn) were not confirmed in any fetched page content. |
| 1.4 | Keyword Targeting & Semantic Relevance | 2/5 | Service page H1s are predominantly hooks or brand philosophy ("AI doesn't fix broken delivery", "Strengthening Your Security From Day One", "At IncrementOne, we design…") rather than leading with the primary keyword; opening body copy explains company methodology rather than framing the buyer's problem, across all nine non-article pages. |
| 1.5 | Internal Linking Structure | 3/5 | Homepage and navigation link to all key service pages; the Approach page links individually to service URLs; however, the rotating article links only to generic destinations (/about-us, /services/the-product-office overview, /training-centre) rather than contextually to the most relevant specific service, and no contextual body-copy links from Perspectives to service pages were detected. |
| 2.1 | HTTP Status Codes | 3/5 | All 10 audited pages returned successful responses; no broken links were detected within the visible internal link structure; however, the Approach page contains a link to /services/leadership-organizational-consulting that was outside audit scope and could not be verified, and full 4xx/5xx detection requires a Screaming Frog crawl. |
| 2.2 | Page Speed & Core Web Vitals | Requires external tool | Run PageSpeed Insights on all 10 audited URLs (mobile and desktop) to assess LCP, CLS, and INP. |
| 2.3 | Mobile Responsiveness | 3/5 | Responsive viewport meta tags confirmed present on Homepage, Product Office, Corporate Training, PDI, and Approach; site uses a consistent responsive framework across pages; actual rendering at 375–414px viewports, tap-target sizing, and CTA functionality cannot be validated from fetched content alone. |
| 2.4 | Structured Data (Schema Markup) | 1/5 | No JSON-LD structured data blocks detected on any of the 10 audited pages; Organization schema, Article/BlogPosting schema (required for the rotating article), LocalBusiness schema, and FAQ schema are all absent — the site has no Rich Results eligibility. |
| 2.5 | Crawlability & Indexability | 3/5 | No noindex signals detected on any audited page (positive); canonical tags could not be confirmed from fetched content on most pages; robots.txt and XML sitemap presence require direct verification outside page content. |
| 3.1 | Direct-Answer Openings | 2/5 | Every audited page opens with a brand philosophy statement, tagline, hook, or generic label; no page answers "what is this service and who is it for?" within the first 40–60 words — the closest approach is the Product Office's problem-framing opening, but it leads with methodology rather than a direct buyer-outcome statement. |
| 3.2 | Fact Density & Quantified Claims | 3/5 | Quantified claims are present but sparse: Corporate Training notes "over 10,000 professionals trained," PDI cites "over 20 years of experience" and "15-minute" assessment, the Cyber Security team is introduced with years-of-experience figures, and the rotating article provides donation distribution percentages; testimonials across all service pages are qualitative without measurable client outcomes. |
| 3.3 | Entity Clarity | 3/5 | "IncrementOne" appears consistently across all pages; Dave Sharrock is named as Founder/CEO on About Us, B Corp, and the rotating article; proprietary frameworks (Product Office, PDI, Path Forward™) are named on their respective pages; however, Canada/Vancouver geography is not prominently established on the homepage or service pages, and About page biographical depth for founder citation-readiness could not be confirmed from fetched content. |
| 3.4 | Extractable Structure (Q&A, Lists, Definitions) | 3/5 | Several pages contain numbered process lists (Corporate Training four-step model, Cyber Security service taxonomy with H3 sub-items, Product Office five capability areas, Approach three-step methodology) and the Product Office includes a "What changes when you get this right?" outcomes section; however, no FAQ sections were detected on any page, and section headers function as topic labels rather than standalone questions or claims. |
| 3.5 | Off-Site Authority | Requires external tool | Run Ahrefs or similar; from page content: Scrum Alliance accredited programs referenced (Corporate Training), podcast "Definitely, Maybe Agile" indexed (Perspectives), and B Corp certification noted — these suggest some external presence but cannot be scored without a backlink and citation audit. |

**Domain averages (current run only — no prior data):**
- SEO: 2.4 / 5
- Web Standards: 2.5 / 5 (4 criteria scored; 2.2 excluded as requires external tool)
- GEO: 2.8 / 5 (4 criteria scored; 3.5 excluded as requires external tool)

---

## Hit List — SEO (Top 5)

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | Missing meta descriptions + short/generic title tags | All 10 pages | 2/5 | 4/5 | Write unique 140–160 character meta descriptions with buyer-intent language for all 10 pages; rewrite six short title tags to 50–60 characters leading with the primary keyword (not "Our Services -" prefix); homepage is the exception for brand-leading title | Directly determines whether buyers click through from search results; meta descriptions alone can lift CTR 5–20% |
| 2 | Keyword-free H1s and methodology-first content framing | All service pages + blog content (9 of 10 pages) | 2/5 | 4/5 | Rewrite each service page's opening paragraph to address the buyer's problem in plain language before introducing methodology; ensure the primary keyword appears in H1, first body paragraph, and at least one H2 on each service page | Controls which buyer queries surface these pages; currently service pages rank for brand terms but are poorly positioned for category and problem queries |
| 3 | Multiple H1s on homepage; non-keyword H1s site-wide | All 10 pages (homepage most critical) | 2/5 | 4/5 | Eliminate the second H1 ("Understand Your Organizational DNA") on the homepage, demoting it to H2; rewrite all H1s that are currently philosophy statements or generic labels to lead with the page's primary keyword | Foundational crawl-signal issue; homepage multiple H1s dilute topical authority and confuse search-engine page classification |
| 4 | Mixed author attribution on blog; thin author credentials | Perspectives listing + rotating article | 3/5 | 4/5 | Replace "IncrementOne" organisational bylines on all Perspectives articles with the named individual author, title, and a short bio; add a link from each author name to their credentials page (Scrum Alliance profile, LinkedIn); update at least the three most-cited testimonials to include one quantified outcome | Google's E-E-A-T assessment directly influences ranking for trust-sensitive B2B queries; named authorship is a minimum requirement |
| 5 | Blog articles link generically; no contextual service links | Perspectives articles | 3/5 | 4/5 | Add contextual body-copy links from each Perspectives article to the most relevant specific service page (e.g., delivery articles → /services/the-product-office); run Screaming Frog to confirm no orphan pages | Distributes PageRank to service pages and helps search engines establish topical relationships between blog and services |

---

## Hit List — Web Standards (Top 4)

*Only 4 criteria were scoreable in this domain (2.2 Core Web Vitals excluded as requires external tool). Fewer than 5 genuine issues exist — not padded to 5.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | No schema markup of any type on any page | All 10 pages | 1/5 | 4/5 | Implement Organization schema (name, URL, logo, contactPoint, sameAs social profiles) on homepage; add Article/BlogPosting schema (author, datePublished, dateModified) to all Perspectives posts; add ProfessionalService schema to service pages; add FAQ schema to any page with Q&A structure; validate in Google Rich Results Test | Schema absence means zero Rich Results eligibility (sitelinks, article cards, FAQ snippets); implementations with zero errors can lift CTR 20–30% |
| 2 | Mobile rendering unverified beyond viewport meta tag | All 10 pages | 3/5 | 5/5 | Run Google Mobile-Friendly Test on each of the 10 audited URLs; manually test at 375px and 414px viewports — specifically audit tap-target sizing on "Let's Talk" and "Book Training" CTAs, navigation menu behaviour, and any form fields | Mobile-first indexing means mobile rendering directly influences rankings; CTAs that fail on mobile directly drop conversion rate |
| 3 | Full broken-link status unverified; one unaudited link detected | All pages; /services/leadership-organizational-consulting specifically | 3/5 | 5/5 | Run Screaming Frog or Ahrefs crawl to surface all 4xx/5xx responses; specifically verify /services/leadership-organizational-consulting (linked from Approach page) resolves to a live 200 page | Broken links on service pages harm crawl budget, UX, and can signal site neglect to Google |
| 4 | Canonical tags, robots.txt, and XML sitemap unconfirmed | All pages | 3/5 | 5/5 | Fetch /robots.txt to confirm key pages are not blocked; verify XML sitemap exists at /sitemap.xml and is submitted to Google Search Console; use View Source on each audited page to confirm canonical tags are self-referential and consistent | Canonical errors cause index duplication; a missing or misconfigured robots.txt can accidentally block entire site sections |

---

## Hit List — GEO (Top 4)

*Only 4 criteria were scoreable in this domain (3.5 Off-Site Authority excluded as requires external tool). Fewer than 5 genuine issues exist — not padded to 5.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|--------------|-------------|------------|-----------------|
| 1 | All pages open with brand philosophy, hooks, or labels — no direct buyer answers | All 10 pages | 2/5 | 4/5 | Rewrite the first paragraph on every service page to answer "What is this, who is it for, and what outcome do they get?" within 40–60 words; on Perspectives articles, front-load the key finding or conclusion in the first paragraph rather than building to it narratively; this change does not require restructuring the rest of the page | Direct-answer openings are the single highest-leverage GEO change — LLMs preferentially select content that answers a query immediately; all 10 pages are currently citation-ineligible for query-response use |
| 2 | Canada/Vancouver geography absent from key pages; founder bio depth unconfirmed | Homepage, About Us, all service pages | 3/5 | 4/5 | Add "based in Vancouver, Canada" or equivalent to homepage hero section, About page opening, and the footer/contact section on all service pages; expand the Dave Sharrock About page biography to include: certifications held, frameworks authored (PDI, Product Office), approximate years of experience, and 2–3 career highlights sufficient for a third party to cite him | Entity completeness is a prerequisite for LLM citation — geography enables localized queries ("agile consulting Vancouver"); a citation-ready founder bio significantly improves probability of being cited in "who are the experts in X" queries |
| 3 | Sparse quantified claims; qualitative-only testimonials | All service pages + rotating article | 3/5 | 4/5 | Add one verifiable statistic, named external framework reference, or attributed client outcome per 150–200 words of body copy across Homepage, Product Office, Corporate Training, and Cyber Security pages; convert at least two testimonials to include a measurable outcome (e.g., delivery cycle time reduction, team satisfaction score, time-to-market improvement) | Fact density is a demonstrated predictor of LLM citation selection in the Princeton GEO study; qualitative testimonials are not citable — quantified ones are |
| 4 | No FAQ sections; section headers are labels not questions | All service pages | 3/5 | 4/5 | Add FAQ sections (minimum 3 Q&A pairs) to Homepage and Product Office; rewrite at least one H2 per service page as a direct question (e.g., "What is the Product Office?" instead of "Product delivery as a foundational capability"); consider adding FAQ schema once FAQ content exists | FAQ and Q&A structure is directly extracted by Google AI Overviews and used as citation blocks by ChatGPT and Perplexity — it is the fastest structural change for GEO impact |

---

## Requires Manual Verification

The following criteria could not be scored from page content alone. These should be checked manually using the indicated tool before the next audit cycle:

| Criterion | Tool needed | Last manually checked |
|-----------|-------------|----------------------|
| 2.2 Page Speed & Core Web Vitals | PageSpeed Insights (run on mobile + desktop for all 10 URLs) | Never |
| 3.5 Off-Site Authority & Citation Signals | Ahrefs or similar (backlink profile + external citation audit) | Never |

---

## Cross-Domain Priority Sequence

If bandwidth is limited this month, action in this order:

1. **Meta descriptions + title tags (SEO 1.1)** — Affects all 10 pages; no meta descriptions exist on any page; this is the highest-leverage single change for search findability and click-through rate.
2. **Direct-answer openings (GEO 3.1)** — Affects all 10 pages; current opening content makes every page citation-ineligible for LLM engines; rewriting opening paragraphs is achievable in one sprint.
3. **Keyword targeting and buyer-problem framing (SEO 1.4)** — Affects all service pages; currently all H1s and opening copy are methodology-led, limiting ranking for non-brand queries.
4. **Structured data / schema markup (Web Standards 2.4)** — Affects all 10 pages; zero implementation means zero Rich Results eligibility; Organization + Article schema can be deployed via one-time site-wide script.
5. **Heading hierarchy: resolve homepage double H1 (SEO 1.2)** — Single highest-priority technical fix; the homepage double H1 dilutes crawl signals on the site's most-linked page and should be resolved as part of any copy refresh.

*Sequence based on: score gap × buyer-journey impact, across all three domains.*

---

*Next audit: June 2026 | Report generated by website-audit-routine v1.0*
