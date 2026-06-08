# IncrementOne Website Audit — June 2026
*Audit date: 2026-06-08 | Standards version: 1.0*
*Rotating article audited: Your Impact In 2025 — https://www.incrementone.com/perspectives/your-impact-in-2025*

---

## Fetch Log

| Page | Status | Notes |
|------|--------|-------|
| Homepage | ✓ Fetched | — |
| The Product Office | ✓ Fetched | — |
| Facilitated Training | ✓ Fetched | — |
| Cyber Security | ✓ Fetched | — |
| Product Delivery Index (PDI) | ✓ Fetched | — |
| About Us | ✓ Fetched | — |
| Approach | ✓ Fetched | — |
| B Corp Business | ✓ Fetched | — |
| Perspectives (blog listing) | ✓ Fetched | Used to select rotating article — no prior reports exist, so the most recently published article ("Your Impact In 2025", May 26 2026) was selected per the rotation rule |
| Your Impact In 2025 (rotating article) | ✓ Fetched | — |

**Fetch failures:** None — all 10 pages in scope loaded successfully. No anomalous/injected instructions were detected in any fetched content.

*Note on assessment limits: the fetch tool converts page HTML to markdown, which strips `<head>` elements (title tags, meta descriptions, viewport/canonical/robots meta tags) from the extracted content for 9 of 10 pages, and does not expose `robots.txt`/sitemap files (which are outside the defined audit scope). Where this materially limited scoring, it is noted against the relevant criterion below.*

---

## Score Summary

| # | Criterion | Current Score | Prior Score | Change | Finding |
|---|-----------|-------------|------------|--------|---------|
| 1.1 | Title Tags & Meta Descriptions | 2/5 | — | — | Meta descriptions were not observable in extracted content for any of the 10 pages, and a `<title>` tag was visible on only one page ("Your Impact In 2025 \| IncrementOne") — too little visible differentiation to indicate a deliberate, page-by-page strategy. |
| 1.2 | Heading Hierarchy | 2/5 | — | — | The Cyber Security page carries two H1s ("Strengthening Your Security From Day One" and "Begin Your Security Transformation"), and the Homepage and PDI page H1s ("People Powered Change"; "AI doesn't fix broken delivery. It accelerates it.") omit their target keywords. |
| 1.3 | E-E-A-T Signals | 3/5 | — | — | Testimonials consistently carry full name, title, and company (strong), but the audited blog article carries an anonymous "IncrementOne" byline with no author bio, and the founder (Dave Sharrock) bio on the About page gives no certifications, track record, or credential links. |
| 1.4 | Keyword Targeting & Semantic Relevance | 3/5 | — | — | Service pages target their core concepts in places (e.g., "Product Office" in the Product Office H1) but the PDI page's H1 and opening paragraph never reference "Product Delivery Index" or "PDI," and several pages open with firm-centric philosophy framing rather than buyer-problem language. |
| 1.5 | Internal Linking Structure | 2/5 | — | — | An almost identical ~20-link set (About, Approach, services, Blog, Podcast, etc.) repeats verbatim across all 10 audited pages, consistent with nav/footer-driven linking; no genuine in-body contextual cross-links (e.g., a service page linking to a relevant Perspectives article on that topic) were observed. |
| 2.1 | HTTP Status Codes | 4/5 | — | — | No broken (4xx/5xx) links were found among the 10 audited pages or their visible internal link targets; roughly a dozen secondary destinations (Training Centre, Podcast, Success Stories, team-member pages, FAQ, Careers, etc.) were linked to but not independently verified — full crawl requires Screaming Frog. |
| 2.2 | Core Web Vitals | Requires external tool | — | — | Run PageSpeed Insights (LCP/CLS/INP cannot be measured from fetched markdown content). |
| 2.3 | Mobile Responsiveness | Requires external tool | — | — | Viewport meta tags and rendered mobile layout are not exposed in the markdown-converted page content for any of the 10 pages; run a mobile-friendly/Lighthouse test to assess. |
| 2.4 | Structured Data | 1/5 | — | — | No JSON-LD or schema markup of any kind was detected on any of the 10 audited pages — including no Organization schema on the homepage and no Article/BlogPosting schema (author, datePublished, dateModified) on the audited Perspectives article. |
| 2.5 | Crawlability & Indexability | Requires external tool | — | — | Canonical tags, noindex signals, robots.txt, and sitemap status were not visible in any fetched page content (these live outside the defined page-fetch scope); verify via Google Search Console. |
| 3.1 | Direct-Answer Openings | 2/5 | — | — | Seven of the ten audited pages (Homepage, Product Office, Cyber Security, PDI, About, Approach, and the rotating article) open with a philosophy/narrative hook rather than a direct statement of what the page is about and who it's for; only the B Corp page opens with a direct announcement. |
| 3.2 | Fact Density & Quantified Claims | 3/5 | — | — | Stats appear unevenly: the Approach page is fact-rich (e.g., "quarterly predictability rose from <60% to >75%," "over 100 organizations"), but the Product Office page contains no quantified metrics at all and the PDI page — the firm's named assessment product — offers only a few isolated numbers with no attributed source. |
| 3.3 | Entity Clarity | 3/5 | — | — | "IncrementOne," "Product Office," and "PDI" are named consistently, but no page in the audited set states the firm's geography (e.g., "Vancouver" or "Canada-based"), and the About page's Dave Sharrock bio is too thin (no certifications, career history, or credential links) to be citation-ready. |
| 3.4 | Extractable Structure | 3/5 | — | — | Numbered processes and bulleted lists are common on service pages (e.g., Product Office's five-area breakdown, Cyber Security's four-stage journey), but no page carries a true FAQ (only "Have Questions?" CTA headers), and the PDI page in particular has no lists, numbered steps, or extractable Q&A content. |
| 3.5 | Off-Site Authority | Requires external tool | — | — | Run Ahrefs or similar. Manually observed: links to LinkedIn (company page and Dave Sharrock's profile), YouTube, Instagram, Facebook, X/Twitter, and partner sites (Cree Cybersecurity, IriusRisk); no Wikipedia/Wikidata entity, Scrum Alliance profile link, or media citation was visible despite the homepage's claim of "Accredited Scrum Alliance programs." |

**Domain averages:**
- SEO: 2.4 / 5 (prior: — , no prior report)
- Web Standards: 2.5 / 5 — averaged over the two scoreable criteria (2.1, 2.4); 2.2/2.3/2.5 require external tools (prior: —)
- GEO: 2.75 / 5 — averaged over the four scoreable criteria (3.1–3.4); 3.5 requires an external tool (prior: —)

*No prior report exists for trend comparison — this is the baseline audit.*

---

## Hit List — SEO (Top 5)

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|-------------|-------------|------------|-----------------|
| 1 | No unique, CTR-driving meta descriptions are visible on any audited page, and only one `<title>` tag could be confirmed | All 10 | 2/5 | 5/5 | Write a unique 140–160 character meta description and a unique 50–60 character, keyword-led title tag for every page in the audit scope | High — directly gates whether a buyer finds and clicks through to the site in search results |
| 2 | Internal linking is effectively identical nav/footer output repeated on every page, with no genuine contextual cross-links | All 10 | 2/5 | 5/5 | Add in-body links from service pages to relevant Perspectives articles (and vice versa) so blog content and service pages reinforce each other contextually, not just via the global nav | Medium — improves crawl signals and helps a buyer who has landed on one page discover related proof points |
| 3 | The Cyber Security page has two H1 tags, and the Homepage/PDI H1s omit their target keywords | Cyber Security, Homepage, PDI | 2/5 | 5/5 | Reduce the Cyber Security page to a single H1 ("Strengthening Your Security From Day One", demoting "Begin Your Security Transformation" to an H2/CTA heading); rework the Homepage and PDI H1s to include their primary keywords ("Product Delivery"/"Product Delivery Index") | Medium — affects how search engines parse page topic and rank key service pages |
| 4 | Author attribution on thought-leadership content is anonymous, and the founder bio lacks depth | Blog/Perspectives article, About Us | 3/5 | 5/5 | Credit "Your Impact In 2025" (and similar posts) to a named author with a short bio; expand Dave Sharrock's About page bio with career history, certifications, and a link to his LinkedIn profile | High — trust signals are what convert a researching buyer into a contact |
| 5 | The PDI page — IncrementOne's flagship assessment product — neither names "Product Delivery Index"/"PDI" in its H1/opening nor frames its content around the buyer's problem in target-keyword language | PDI | 3/5 | 5/5 | Rewrite the PDI H1 and opening paragraph to lead with "Product Delivery Index" and the buyer problem it solves, with supporting semantic variants in H2s | Medium — a page meant to rank for its own named product currently doesn't target that name |

---

## Hit List — Web Standards (Top 5)

*Only two criteria in this domain could be scored from page content (2.1, 2.4); the remaining three (2.2, 2.3, 2.5) require external tools and are listed under "Requires Manual Verification" instead. Per the selection rules, fewer than five genuine scoreable issues exist, so only those two are listed below.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|-------------|-------------|------------|-----------------|
| 1 | No structured data (JSON-LD/schema markup) of any kind was detected on any audited page — no Organization schema on the homepage, no Article/BlogPosting schema on blog content | All 10 | 1/5 | 5/5 | Add Organization schema (name, URL, logo, contact, social profiles) to the homepage and Article/BlogPosting schema (author, datePublished, dateModified) to Perspectives posts; add FAQ schema where genuine Q&A content exists | High — schema drives rich results, knowledge-panel eligibility, and is increasingly how AI engines verify entity facts |
| 2 | No broken links found among audited pages, but ~12 secondary linked destinations were not independently status-checked | All 10 (link targets: Training Centre, Podcast, Success Stories, team-member pages, FAQ, Careers, Legal, etc.) | 4/5 | 5/5 | Run a full Screaming Frog crawl to confirm 200 status on every internal link target, including the secondary pages not in this month's audit scope | Low — hygiene issue; current evidence shows no problems, this simply closes the verification gap |

---

## Hit List — GEO (Top 5)

*Only four criteria in this domain could be scored from page content (3.1–3.4); 3.5 requires an external tool and is listed under "Requires Manual Verification." Per the selection rules, fewer than five genuine scoreable issues exist, so four are listed below.*

| # | Issue | Pages Affected | Current Score | Target Score | What to Fix | Estimated Impact |
|---|-------|---------------|-------------|-------------|------------|-----------------|
| 1 | Seven of ten audited pages open with a philosophy/narrative hook instead of answering "what is this, who is it for" in the first 40–60 words | Homepage, Product Office, Cyber Security, PDI, About Us, Approach, rotating article | 2/5 | 5/5 | Rewrite opening paragraphs on these pages to state plainly what the page/service/post is about and who it serves, before pivoting to philosophy or narrative | High — direct-answer openings are what LLMs and skimming buyers latch onto first; this is the single biggest lever for both AI citation and buyer attention |
| 2 | No page states IncrementOne's geography (e.g., Vancouver/Canada), and the founder bio on About Us lacks the depth needed to be cited as an authoritative source | All 10 (geography); About Us (founder bio) | 3/5 | 5/5 | Add an explicit geography statement (city/country) to the About page and footer/Organization schema; expand Dave Sharrock's bio with career history, certifications, and credential links | Medium — entity clarity is what lets LLMs correctly place and cite the firm and its principal |
| 3 | Fact density is uneven — the Product Office page has no quantified claims at all, and the PDI page (the firm's named diagnostic product) offers only isolated numbers with no attributed source | Product Office, PDI | 3/5 | 5/5 | Add specific, sourced statistics, named research, or documented client outcomes at roughly 150–200 word intervals on these two pages, mirroring the fact density already present on the Approach page | Medium — quantified, attributed claims are a primary driver of LLM citation and buyer trust in qualitative service categories |
| 4 | The PDI page has no FAQ, bulleted list, numbered process, or other extractable structure for LLMs to lift as a discrete chunk | PDI | 3/5 | 5/5 | Add an extractable "What is the PDI?" / "What you get back" Q&A or bulleted breakdown (the page already has natural candidates: the five dimensions, the 15-minute assessment, the AI loop) and apply FAQ schema | Medium — this is the page most likely to be queried directly ("what is the Product Delivery Index"), and it currently offers nothing an LLM can extract cleanly |

---

## Requires Manual Verification

The following criteria could not be scored from page content alone. These should be checked manually using the indicated tool before the next audit cycle:

| Criterion | Tool needed | Last manually checked |
|-----------|-------------|----------------------|
| 2.2 Core Web Vitals | PageSpeed Insights | Never |
| 2.3 Mobile Responsiveness | Google Mobile-Friendly Test / Lighthouse | Never |
| 2.5 Crawlability & Indexability | Google Search Console (canonical tags, robots.txt, sitemap, noindex) | Never |
| 3.5 Off-Site Authority | Ahrefs or similar (backlink profile, Wikipedia/Wikidata, Scrum Alliance, media citations) | Never |

---

## Cross-Domain Priority Sequence

If bandwidth is limited this month, action in this order:

1. Add Organization schema to the homepage and Article/BlogPosting schema to Perspectives posts — the single largest scored gap on the site (2.4: 1/5).
2. Write unique, keyword-led title tags and CTR-driving meta descriptions for all 10 audited pages — affects every page's ability to be found in search (1.1: 2/5).
3. Rewrite opening paragraphs on the seven philosophy-led pages (Homepage, Product Office, Cyber Security, PDI, About Us, Approach, rotating article) to lead with a direct answer (3.1: 2/5).
4. Replace the repeated nav-driven link list with genuine in-body contextual cross-links between service pages and Perspectives articles (1.5: 2/5).
5. Fix the duplicate-H1 issue on the Cyber Security page and align the Homepage and PDI H1s to their target keywords (1.2: 2/5).

*Sequence based on: score gap × buyer-journey impact, across all three domains.*

---

*Next audit: July 2026 | Report generated by website-audit-routine v1.0*
