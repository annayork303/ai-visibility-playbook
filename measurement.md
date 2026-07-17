# Measurement & Milestones

What success looks like at each stage — and how to know if it's working before you hit month 6.

## 30 / 60 / 90-day milestones

**Day 30 — Foundation set**

- Critical Elements 1–4 done on top 5 articles
- Schema markup live and validated
- GA4 AI channel grouping configured
- Baseline citation count recorded (even if zero)
- Weekly manual check routine established

**Day 60 — First citations**

- 1–5 citations appearing (solo) or 5–15 (team)
- High Priority Elements 5–8 started
- Author bios and expert pages published
- First original data asset created
- AI traffic visible in GA4 dashboard

**Day 90 — Compounding growth**

- 15–30% citation rate on optimized content
- AI traffic converting at 2–5x organic rate
- All High Priority Elements (5–11) complete
- Enhancement elements (12–17) underway
- Repeatable update process in place

## Key metrics to track

| Metric | How to measure | Frequency | Target |
|---|---|---|---|
| Citation count | Manual checking + citation tracking tool | Weekly | Growing week-on-week |
| Citation velocity | New citations per week over time | Weekly | Accelerating by month 2 |
| Platform distribution | Test across ChatGPT, Perplexity, Claude, Gemini | Weekly | Cited on 2+ platforms |
| AI-attributed traffic | GA4 custom channel grouping | Monthly | Growing month-on-month |
| AI conversion rate | GA4: AI traffic vs organic | Monthly | 2–5x higher than organic |

## GA4 AI traffic setup

```text
1. GA4 → Admin → Data Streams → Web → Configure tag settings
2. Create custom dimension: ai_source
3. Add UTM parameters: ?utm_source=chatgpt (or perplexity / claude)
4. Create custom channel grouping:
   Channel name: "AI Search"
   Conditions: Source contains "chatgpt" OR "perplexity" OR "claude"
5. Set up conversion goals to compare AI vs organic conversion rates
```

## Tools by budget

| Budget | Tools | Monthly cost |
|---|---|---|
| Free | Google Search Console, GA4, manual platform checking | $0 |
| Starter | Semrush + schema generator | $100–150 |
| Growth | Answer-engine insights tooling + Semrush + schema tools | $500–800 |

*Part of [The AI Visibility Playbook](../README.md) · CC BY 4.0*
