# The 23-Element Framework

All 23 elements, organized by priority tier. Implement in order: Critical first (with Technical in parallel), then High Priority over ~3 months, then Enhancement.

---

## 🔴 Critical Elements (1–4)

**Do these before anything else — no exceptions.** Without all four Critical Elements in place, citation probability stays below 5% regardless of everything else you do. In the study, a 2-person team went from 0% to 28% citations in 90 days using *only* these four.

### Element 1 — User Intent Match

Answer the exact question users ask. Research real queries from Reddit, support tickets, sales calls, and People Also Ask. No intent match = no citation, no matter how good the content is.

*Effort: 30–60 min/article · Non-negotiable*

### Element 2 — Direct Answer in First 100 Words

Complete, self-contained answer in the first 100 words with **zero links**. LLMs extract 100-word chunks, and the opening block gets the highest relevance score. 91% of cited content follows this pattern exactly.

**The Direct Answer Formula:**

| Part | Length | What to write |
|---|---|---|
| Direct Answer | 20–30 words | State the answer clearly in 1–2 sentences. Be specific, not vague. |
| Essential Context | 40–50 words | Key facts, statistics, or qualifications that support the answer. |
| Preview | 20–30 words | Briefly mention what the article covers in detail below. |

**The link-free rule:** 91% of cited answer blocks contain ZERO hyperlinks. Links signal to the LLM that the authoritative information is elsewhere — which reduces your chunk's citability. Place ALL links after the first 100 words.

→ Fill-in template: [templates/direct-answer-template.md](templates/direct-answer-template.md)

*Effort: 15–20 min/article · 91% of cited posts*

### Element 3 — Content Freshness

Update every 6 months. Display "Last updated: [date]" prominently at the top. Make real changes — refresh stats, update examples, fix broken links. AI models detect date-only updates and may penalize them.

*Effort: 30–90 min/update · Strong trust signal*

### Element 4 — Scannability

Use H2/H3 headings, bullets, and tables throughout. Present all data in tables, not prose — tables increase citation probability by 40%. Keep paragraphs to 2–4 sentences maximum.

*Effort: 20–30 min/article · +40% with tables*

---

## 🟠 High Priority Elements (5–11)

Add these after the Critical Elements. Work through them over ~3 months. Each one independently adds 8–12% to your citation probability.

### Element 5 — Comprehensive Coverage

Cover all related follow-up questions in a single article. Include a dedicated FAQ section answering the top 5–10 related questions users have after reading.

### Element 6 — Expert Author (E-E-A-T)

Detailed author bios with credentials, photos, and social links. Named author, full bio page, and an About Us page that clearly establishes topical expertise.

### Element 7 — Original Data

Conduct surveys, analyze internal data, publish proprietary research. 52.2% of cited posts contain original data. Present it in tables or charts with the methodology explained.

### Element 8 — Authoritative Citations

Back every major claim with primary sources — government sites, academic papers, original studies. Use descriptive anchor text. Avoid aggregators as your source.

### Element 9 — Transparent Methodology

Explain how you collected data or reached conclusions. State sample sizes, acknowledge limitations. Claude specifically favors transparent methodology as a trust signal.

### Element 10 — Q&A Format

Use questions as H2/H3 headings throughout. Add a dedicated FAQ section with FAQPage schema markup. This mirrors how users phrase queries to AI assistants directly.

### Element 11 — Hero Resource

Create one citable asset: an original chart, diagram, template, calculator, or video. Must be unique, clearly labeled, with descriptive alt text.

---

## 🔵 Enhancement Elements (12–17)

Polish and authority signals. Add these after Critical and High Priority elements are solid.

### Element 12 — Structured Formatting (HTML5)

Use semantic HTML: `<article>`, `<section>`, `<header>`. Provide clear attribution throughout your content.

### Element 13 — Factual Precision

Replace "many" with exact figures. Replace "recently" with dates. Use specific numbers, verifiable claims, and named sources throughout every section.

### Element 14 — Social Proof

Include testimonials with real names and photos. Write detailed case studies with specific, quantified metrics — not vague success stories.

### Element 15 — Problem-Solution Framing

Frame each major section around a user problem (H2 as a question) followed immediately by a direct solution. Mirror how users actually think about their challenges.

### Element 16 — Value Anchoring

Focus on ROI and measurable transformation, not just features. Quantify every outcome clearly and specifically. Show the "after" state.

### Element 17 — Conversion Elements

CTA above the fold, transparent pricing, lead magnets, human support options. Primarily applicable to landing pages and product pages.

---

## 🟢 Technical Layer (18–23)

The foundation that enables all other elements. Implement these **early** — in parallel with the Critical Elements.

### Element 18 — Schema Markup

JSON-LD structured data tells AI exactly what your content is about. Apply Article schema on all posts, FAQPage on Q&A sections, HowTo on guides.

→ Copy-paste code: [snippets/](snippets/)

### Element 19 — Page Speed (<2.5s LCP)

Compress images to WebP, enable browser caching, use a CDN (Cloudflare, AWS CloudFront), minify CSS/JS. Critical for crawl budget and user-experience signals.

### Element 20 — Mobile Responsive

Must pass Google's Mobile-Friendly Test. Non-negotiable — mobile traffic is the majority for most sites.

### Element 21 — HTTPS

Install an SSL certificate and enforce HTTPS redirects across the entire domain. Non-secure sites are filtered out at source qualification.

### Element 22 — Clean URL Structure

Short, semantic URLs: `/blog/seo-cost/` not `/p?id=12345`. URLs should clearly describe the content.

### Element 23 — Meta & Sitemap

Optimized meta titles (55–60 chars) and descriptions (150–160 chars). Maintain an XML sitemap and a clear internal linking strategy.

---

**Next steps:** run the [audit checklist](CHECKLIST.md) on your top articles, then follow the [implementation roadmap](docs/roadmap.md) for your team size.

*Part of [The AI Visibility Playbook](README.md) by Anna York / Citation School · CC BY 4.0*
